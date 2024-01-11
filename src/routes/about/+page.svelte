<script>
    import Navbars from "../../template/Navbars.svelte";
    import { Center, Text, Stack, Image, Flex } from '@svelteuidev/core';
    let url = "https://www.kcl.ac.uk/newimages/person-profile/2022b/harry.x619e9d58.png?w=160&h=160&f=webp"
</script>
<Navbars/>

<Center class="p-20">
    <Stack align="strech" spacing="xs">
        <Flex gap="md">
            <Image width={200} height={200} src={url} alt='Harry Sharma' usePlaceholder radius={100}>
                <svelte:fragment slot='placeholder'>
                    <Text>This image would have changed your life</Text>
                </svelte:fragment>
            </Image>
            <Stack align="strech" spacing="xs">
                <Text color="dimmed" size="sm">
                    Harry Sharma
                </Text>
                <Text color="dimmed" size="sm">
                    21 years old
                </Text>
                <Text color="dimmed" size="sm">
                    London, UK
                </Text>
                <Text color="dimmed" size="sm">
                    BSc Computer Science
                </Text>
                <Text color="dimmed" size="sm">
                    King's College London
                </Text>
            </Stack>
        </Flex>   
    </Stack>
</Center>
