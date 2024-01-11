<script>
    import Navbars from "../../template/Navbars.svelte";
    import { Center, Text, Timeline, Stack } from '@svelteuidev/core';
</script>
<Navbars/>
<div class="flex justify-center content-center p-32">
    <Center>
        <Timeline active={3} color="teal" bulletSize={15} lineWidth={2}>
            <Timeline.Item title="GCSE">
                    <Stack align="strech" spacing="xs">
                                <Text color="dimmed" size="sm">
                                        2014-2019 The Duston School
                                </Text>
                                <Text color="dimmed" size="sm">• Maths: 8</Text>
                                <Text color="dimmed" size="sm">• Geography: 9</Text>
                                <Text color="dimmed" size="sm">• Combined Science: 8/7</Text>
                                <Text color="dimmed" size="sm">• History: 8</Text>
                                <Text color="dimmed" size="sm">• English Literature: 7</Text>
                                <Text color="dimmed" size="sm">• English Language: 6</Text>
                                <Text color="dimmed" size="sm">• Computer Science: 6</Text>
                                <Text color="dimmed" size="sm">• Business Studies LM2</Text>
                    </Stack>
            </Timeline.Item>
            <Timeline.Item title="A-Levels">
                    <Stack align="strech" spacing="xs">
                        <Text color="dimmed" size="sm">
                            2019-2021 The Duston School
                        </Text>
                        <Text color="dimmed" size="sm">• Maths: A</Text>
                        <Text color="dimmed" size="sm">• Computer Science: B</Text>
                        <Text color="dimmed" size="sm">• Chemistry: B</Text>

                    </Stack>
            </Timeline.Item>
            <Timeline.Item title="BSc Computer Science">
                    <Stack align="strech" spacing="xs">
                        <Text color="dimmed" size="sm">
                            2021-2023 King's College London
                        </Text>
                        <Text color="dimmed" size="sm">First Year:</Text>
                        <Text color="dimmed" size="sm">• --Too be filled-- </Text>
                        <Text color="dimmed" size="sm">• --Too be filled-- </Text>
                        <Text color="dimmed" size="sm">• --Too be filled-- </Text>
                        <Text color="dimmed" size="sm">• --Too be filled-- </Text>
                        <Text color="dimmed" size="sm">• --Too be filled-- </Text>
                        <Text color="dimmed" size="sm">• --Too be filled-- </Text>
                        <Text color="dimmed" size="sm">• --Too be filled-- </Text>
                        <Text color="dimmmed" size="sm">Second Year:</Text>
                        <Text color="dimmed" size="sm">• --Too be filled-- </Text>
                        <Text color="dimmed" size="sm">• --Too be filled-- </Text>
                        <Text color="dimmed" size="sm">• --Too be filled-- </Text>
                        <Text color="dimmed" size="sm">• --Too be filled-- </Text>
                        <Text color="dimmed" size="sm">• --Too be filled-- </Text>
                        <Text color="dimmed" size="sm">• --Too be filled-- </Text>
                        <Text color="dimmed" size="sm">• --Too be filled-- </Text>


                    </Stack>
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
