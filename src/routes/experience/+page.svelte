<script>
    import Navbars from "../../template/Navbars.svelte";
    import { Center, Text, Timeline } from '@svelteuidev/core';
</script>
<Navbars/>
<div class="flex justify-center content-center p-32">
    <Center>
        <Timeline active={3} color="teal" bulletSize={15} lineWidth={2}>
            <Timeline.Item title="GCSE">
                    <Text color="dimmed" size="sm">
                            2014-2019 The Duston School
                    </Text>
            </Timeline.Item>
            <Timeline.Item title="A-Levels">
                    <Text color="dimmed" size="sm">
                            2019-2021 The Duston School
                    </Text>
            </Timeline.Item>
            <Timeline.Item title="BSc Computer Science">
                    <Text color="dimmed" size="sm">
                        2021-2023 King's College London
                    </Text>
            </Timeline.Item>
            <Timeline.Item title="Research Operations Engineer Intern">
                    <Text color="dimmed" size="sm">
                        2023-2024 King's College London
                    </Text>
            </Timeline.Item>
            <Timeline.Item title="BSc Computer Science">
                <Text color="dimmed" size="sm">
                    2024-2025 King's College London
                </Text>
            </Timeline.Item>


        </Timeline>
    </Center>
</div>
