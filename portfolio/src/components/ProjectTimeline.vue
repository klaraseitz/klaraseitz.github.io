<template>
    <div>
        <v-timeline reverse>
            <v-timeline-item fill-dot :icon="'mdi-code-braces'" :color="'amber'">
                <span slot="opposite">2020</span>
                <v-card class="elevation-2">
                    <v-card-title class="headline">Virtual Crochet</v-card-title>
                    <v-card-subtitle class="pb-1">Masterthesis</v-card-subtitle>
                    <v-card-text class="text--primary">
                        Building digital support for creating instructions for patterns of the handcrafting technique crochet.
                        Designing a digital representation of crochet patterns, based on a graph structure used as domain specific language, to allow domain specific support for crochet pattern designers during the pattern creation and instruction writing process.  As proof-of-concept, a projectional editor uses the graph to represent patterns and a diagramming system (internationally known crochet charts) to visualize them in 2D and 3D.
                    </v-card-text>
                    <v-card-actions>
                        <v-btn href="/crochet" text>
                            <v-icon left>mdi-play-circle-outline</v-icon> Try the Prototype
                        </v-btn>
                        <v-btn href="https://github.com/klaraseitz/LayerwiseCrochet" text>
                            <v-icon left>mdi-code-json</v-icon> View the Code
                        </v-btn>
                    </v-card-actions>

                </v-card>
            </v-timeline-item>

            <v-timeline-item fill-dot :icon="'mdi-code-braces'" :color="'amber'">
                <span slot="opposite">2017</span>
                <v-card class="elevation-2">
                    <v-card-title class="headline">Haptic Squatting</v-card-title>
                    <v-card-subtitle class="pb-1">Masterproject</v-card-subtitle>
                    <v-card-text class="text--primary">
                        Scanning the real world with a Holo Lens, fitting virtual rooms with given requirements into the available space, connecting rooms with paths and using existing objects to create more realistic user experiences through haptic feedback.
                    </v-card-text>
                </v-card>
            </v-timeline-item>

            <v-timeline-item fill-dot :icon="'mdi-school-outline'" :color="'green'">
                <span slot="opposite">2016-2020</span>
                <v-card class="elevation-2">
                    <v-card-title class="headline">Master in IT-Systems Engineering</v-card-title>
                    <v-card-subtitle class="pb-1">Hasso Plattner Institute in Potsdam, Germany</v-card-subtitle>
                </v-card>
            </v-timeline-item>

            <v-timeline-item fill-dot :icon="'mdi-school-outline'" :color="'green'">
                <span slot="opposite">2019</span>
                <v-card class="elevation-2">
                    <v-card-title class="headline">Erasmus at University of Jyväskylä, Finland</v-card-title>
                    <v-card-text class="text--primary">
                        Courses: SOA and Cloud computing, IoT/Embedded Security, Project and Change Management, Usability and Web, Finnish Language A1 - A2
                    </v-card-text>
                </v-card>
            </v-timeline-item>

            <v-timeline-item fill-dot :icon="'mdi-briefcase-variant-outline'" :color="'indigo'">
                <span slot="opposite">2018-2019</span>
                <v-card class="elevation-2">
                    <v-card-title class="headline">Working student at mTOMADY in Berlin, Germany</v-card-title>
                    <v-card-text class="text--primary">
                        Supporting the developer team of the medical startup from Doctors for Madagascar. Developing a Ruby Application to help digitalize and facilitate the payment process in healthcare facilities in Madagascar.
                    </v-card-text>
                </v-card>
            </v-timeline-item>

            <v-timeline-item fill-dot :icon="'mdi-briefcase-variant-outline'" :color="'indigo'">
                <span slot="opposite">2017</span>
                <v-card class="elevation-2">
                    <v-card-title class="headline">University of Bristol, UK</v-card-title>
                    <v-card-subtitle class="pb-1">Internship</v-card-subtitle>
                    <v-card-text class="text--primary">
                        Research Internship at the Human-Computer-Interaction-Chair with the topic of 3D printing mechanical elements such as springs and gears.
                    </v-card-text>
                </v-card>
            </v-timeline-item>

            <v-timeline-item fill-dot :icon="'mdi-briefcase-variant-outline'" :color="'indigo'">
                <span slot="opposite">2016</span>
                <v-card class="elevation-2">
                    <v-card-title class="headline">Pidoco in Berlin, Germany</v-card-title>
                    <v-card-subtitle class="pb-1">Internship</v-card-subtitle>
                    <v-card-text class="text--primary">
                        Development of new front end functionalities within the website wireframe prototyping tool.
                    </v-card-text>
                </v-card>
            </v-timeline-item>

            <v-timeline-item fill-dot :icon="'mdi-briefcase-variant-outline'" :color="'indigo'">
                <span slot="opposite">2016</span>
                <v-card class="elevation-2">
                    <v-card-title class="headline">Factory Data in Lleida, Spain</v-card-title>
                    <v-card-subtitle class="pb-1">IAESTE Internship</v-card-subtitle>
                    <v-card-text class="text--primary">
                        Work in the field of automotive aftermarket data analytics. Within this project the existing functions and representation of the data in a relational database were migrated to a graph database using NEO4J.
                    </v-card-text>
                </v-card>
            </v-timeline-item>


            <v-timeline-item fill-dot :icon="'mdi-code-braces'" :color="'amber'">
                <span slot="opposite">2016</span>
                <v-card class="elevation-2">
                    <v-card-title class="headline">Platener</v-card-title>
                    <v-card-subtitle class="pb-1">Bachelorproject</v-card-subtitle>
                    <v-card-text class="text--primary">
                        Webapp which converts 3D models to 2D plates which can be cut with a lasercutter and assembled to approximate the original model for faster prototyping.
                    </v-card-text>
                </v-card>
            </v-timeline-item>

            <v-timeline-item fill-dot :icon="'mdi-school-outline'" :color="'green'">
                <span slot="opposite">2013-2016</span>
                <v-card class="elevation-2">
                    <v-card-title class="headline">Bachelor in IT-Systems Engineering</v-card-title>
                    <v-card-subtitle class="pb-1">Hasso Plattner Institute in Potsdam, Germany</v-card-subtitle>
                </v-card>
            </v-timeline-item>
        </v-timeline>
    </div>
</template>

<script>
    export default {
        name: "ProjectTimeline"
    }
</script>

<style scoped>

</style>