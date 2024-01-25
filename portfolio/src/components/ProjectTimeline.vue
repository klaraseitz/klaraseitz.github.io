<template>
  <div>
    <v-timeline reverse>
      <v-timeline-item
        fill-dot
        :icon="'mdi-rocket-launch-outline'"
        :color="'purple'"
      >
        <span slot="opposite">2022-Today</span>
        <v-card class="elevation-2">
          <v-card-title class="headline">ChartCrafter</v-card-title>
          <v-card-subtitle class="pb-1">Founder</v-card-subtitle>
          <v-card-text class="text--primary">
            Having conceptualized and created an innovative crochet chart editor
            for the master's thesis, the EXIST founders' grant allowed devotion
            of a full year to its full-time development. With the basic
            functions done, payment was incorporated, laying the foundation for
            supplementary income. In future the project development will be
            advanced on a part-time basis.
            <div class="ma-1">
              <v-chip class="ma-1"> Vuejs </v-chip>
              <v-chip class="ma-1"> Nodejs </v-chip>
              <v-chip class="ma-1"> Heroku </v-chip>
              <v-chip class="ma-1"> Netlify </v-chip>
              <v-chip class="ma-1"> AWS </v-chip>
            </div>
          </v-card-text>

          <v-card-actions>
            <v-btn href="https://www.chartcrafter.org" text>
              <v-icon left>mdi-web</v-icon> View ChartCrafter's Website
            </v-btn>
          </v-card-actions>
        </v-card>
      </v-timeline-item>

      <v-timeline-item
        fill-dot
        :icon="'mdi-briefcase-variant-outline'"
        :color="'indigo'"
      >
        <span slot="opposite">2020-2022</span>
        <v-card class="elevation-2">
          <v-card-title class="headline">KoRo</v-card-title>
          <v-card-subtitle class="pb-1">Webdeveloper</v-card-subtitle>
          <v-card-text class="text--primary">
            The main tasks were the development of software projects for the
            KoRo Shop using Shopware6 and internal Tools using React and Node.
            Additionally, I optimized the IT infrastructure on AWS and Heroku.

            <div class="ma-1">
              <v-chip class="ma-1"> React </v-chip>
              <v-chip class="ma-1"> Nodejs </v-chip>
              <v-chip class="ma-1"> Threejs </v-chip>
              <v-chip class="ma-1"> D3 </v-chip>
              <v-chip class="ma-1"> Heroku </v-chip>
              <v-chip class="ma-1"> AWS </v-chip>
              <v-chip class="ma-1"> Shopware6 </v-chip>
            </div>
          </v-card-text>
        </v-card>
      </v-timeline-item>

      <v-timeline-item fill-dot :icon="'mdi-code-braces'" :color="'amber'">
        <span slot="opposite">2020</span>
        <v-card class="elevation-2">
          <v-card-title class="headline">Virtual Crochet</v-card-title>
          <v-card-subtitle class="pb-1">Masterthesis</v-card-subtitle>
          <v-card-text class="text--primary">
            Building digital support for creating instructions for patterns of
            the handcrafting technique crochet. Designing a digital
            representation of crochet patterns, based on a graph structure used
            as domain specific language, to allow domain specific support for
            crochet pattern designers during the pattern creation and
            instruction writing process. As proof-of-concept, a projectional
            editor uses the graph to represent patterns and a diagramming system
            (internationally known crochet charts) to visualize them in 2D and
            3D.

            <div class="ma-1">
              <v-chip class="ma-1"> Angular </v-chip>
              <v-chip class="ma-1"> Nodejs </v-chip>
              <v-chip class="ma-1"> Threejs </v-chip>
              <v-chip class="ma-1"> D3 </v-chip>
            </div>
          </v-card-text>
          <v-card-actions>
            <v-btn href="/crochet" text>
              <v-icon left>mdi-play-circle-outline</v-icon> Try the Prototype
            </v-btn>
            <v-btn href="/examples" text>
              <v-icon left>mdi-download</v-icon> examples
            </v-btn>
            <v-btn href="https://github.com/klaraseitz/LayerwiseCrochet" text>
              <v-icon left>mdi-code-json</v-icon> View the Code
            </v-btn>
            <v-btn
              href="https://publishup.uni-potsdam.de/frontdoor/index/index/docId/49253"
              text
            >
              <v-icon left>mdi-note-text-outline</v-icon> View Publication
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
            Scanning the real world with a Holo Lens, fitting virtual rooms with
            given requirements into the available space, connecting rooms with
            paths and using existing objects to create more realistic user
            experiences through haptic feedback.

            <div class="ma-1">
              <v-chip class="ma-1"> HoloLens </v-chip>
              <v-chip class="ma-1"> Unity </v-chip>
              <v-chip class="ma-1"> C# </v-chip>
            </div>
          </v-card-text>
        </v-card>
      </v-timeline-item>

      <v-timeline-item fill-dot :icon="'mdi-school-outline'" :color="'green'">
        <span slot="opposite">2016-2020</span>
        <v-card class="elevation-2">
          <v-card-title class="headline"
            >Master in IT-Systems Engineering</v-card-title
          >
          <v-card-subtitle class="pb-1"
            >Hasso Plattner Institute in Potsdam, Germany</v-card-subtitle
          >
          <v-card-text>
            <div class="ma-1">
              <v-chip class="ma-1"> Human Computer Interaction </v-chip>
              <v-chip class="ma-1"> 3D Printing </v-chip>
              <v-chip class="ma-1"> Lasercutting </v-chip>
              <v-chip class="ma-1"> SQL </v-chip>
            </div>
          </v-card-text>
        </v-card>
      </v-timeline-item>

      <v-timeline-item fill-dot :icon="'mdi-school-outline'" :color="'green'">
        <span slot="opposite">2019</span>
        <v-card class="elevation-2">
          <v-card-title class="headline"
            >Erasmus at University of Jyväskylä, Finland</v-card-title
          >
          <v-card-text class="text--primary">
            Courses: SOA and Cloud computing, IoT/Embedded Security, Project and
            Change Management, Usability and Web, Finnish Language A1 - A2

            <div class="ma-1">
              <v-chip class="ma-1"> Cloud Systems </v-chip>
              <v-chip class="ma-1"> IoT </v-chip>
              <v-chip class="ma-1"> Project Management </v-chip>
            </div>
          </v-card-text>
        </v-card>
      </v-timeline-item>

      <v-timeline-item
        fill-dot
        :icon="'mdi-briefcase-variant-outline'"
        :color="'indigo'"
      >
        <span slot="opposite">2018-2019</span>
        <v-card class="elevation-2">
          <v-card-title class="headline"
            >Working student at mTOMADY in Berlin, Germany</v-card-title
          >
          <v-card-text class="text--primary">
            Supporting the developer team of the medical startup from Doctors
            for Madagascar. Developing a Ruby Application to help digitalize and
            facilitate the payment process in healthcare facilities in
            Madagascar.

            <div class="ma-1">
              <v-chip class="ma-1"> Ruby </v-chip>
              <v-chip class="ma-1"> SQL </v-chip>
            </div>
          </v-card-text>
        </v-card>
      </v-timeline-item>

      <v-timeline-item
        fill-dot
        :icon="'mdi-briefcase-variant-outline'"
        :color="'indigo'"
      >
        <span slot="opposite">2017</span>
        <v-card class="elevation-2">
          <v-card-title class="headline"
            >University of Bristol, UK</v-card-title
          >
          <v-card-subtitle class="pb-1">Internship</v-card-subtitle>
          <v-card-text class="text--primary">
            Research Internship at the Human-Computer-Interaction-Chair with the
            topic of 3D printing mechanical elements such as springs and gears.

            <div class="ma-1">
              <v-chip class="ma-1"> Research </v-chip>
              <v-chip class="ma-1"> 3D Printing </v-chip>
              <v-chip class="ma-1"> 3D Modeling </v-chip>
              <v-chip class="ma-1"> Pure Data (Pd) </v-chip>
            </div>
          </v-card-text>
        </v-card>
      </v-timeline-item>

      <v-timeline-item
        fill-dot
        :icon="'mdi-briefcase-variant-outline'"
        :color="'indigo'"
      >
        <span slot="opposite">2016</span>
        <v-card class="elevation-2">
          <v-card-title class="headline"
            >Pidoco in Berlin, Germany</v-card-title
          >
          <v-card-subtitle class="pb-1">Internship</v-card-subtitle>
          <v-card-text class="text--primary">
            Development of new front end functionalities within the website
            wireframe prototyping tool.

            <div class="ma-1">
              <v-chip class="ma-1"> Scrum </v-chip>
              <v-chip class="ma-1"> JavaScript </v-chip>
              <v-chip class="ma-1"> CSS </v-chip>
            </div>
          </v-card-text>
        </v-card>
      </v-timeline-item>

      <v-timeline-item
        fill-dot
        :icon="'mdi-briefcase-variant-outline'"
        :color="'indigo'"
      >
        <span slot="opposite">2016</span>
        <v-card class="elevation-2">
          <v-card-title class="headline"
            >Factory Data in Lleida, Spain</v-card-title
          >
          <v-card-subtitle class="pb-1">IAESTE Internship</v-card-subtitle>
          <v-card-text class="text--primary">
            Work in the field of automotive aftermarket data analytics. Within
            this project the existing functions and representation of the data
            in a relational database were migrated to a graph database using
            NEO4J.

            <div class="ma-1">
              <v-chip class="ma-1"> Neo4j (graph db) </v-chip>
              <v-chip class="ma-1"> Cypher (query language) </v-chip>
              <v-chip class="ma-1"> SQL </v-chip>
            </div>
          </v-card-text>
        </v-card>
      </v-timeline-item>

      <v-timeline-item fill-dot :icon="'mdi-code-braces'" :color="'amber'">
        <span slot="opposite">2016</span>
        <v-card class="elevation-2">
          <v-card-title class="headline">Platener</v-card-title>
          <v-card-subtitle class="pb-1">Bachelorproject</v-card-subtitle>
          <v-card-text class="text--primary">
            Webapp which converts 3D models to 2D plates which can be cut with a
            lasercutter and assembled to approximate the original model for
            faster prototyping.

            <div class="ma-1">
              <v-chip class="ma-1"> Coffeescript </v-chip>
              <v-chip class="ma-1"> Nodejs </v-chip>
              <v-chip class="ma-1"> 3D printing </v-chip>
              <v-chip class="ma-1"> Lasercutting </v-chip>
              <v-chip class="ma-1"> 3D visualization </v-chip>
            </div>
          </v-card-text>
          <v-card-actions>
            <v-btn
              href="https://hcie.csail.mit.edu/research/platener/platener.html"
              text
            >
              <v-icon left>mdi-note-text-outline</v-icon> View Related
              Publication
            </v-btn>
          </v-card-actions>
        </v-card>
      </v-timeline-item>

      <v-timeline-item fill-dot :icon="'mdi-school-outline'" :color="'green'">
        <span slot="opposite">2013-2016</span>
        <v-card class="elevation-2">
          <v-card-title class="headline"
            >Bachelor in IT-Systems Engineering</v-card-title
          >
          <v-card-subtitle class="pb-1"
            >Hasso Plattner Institute in Potsdam, Germany</v-card-subtitle
          ><v-card-text>
            <div class="ma-1">
              <v-chip class="ma-1"> Git </v-chip>
              <v-chip class="ma-1"> SQL </v-chip>
              <v-chip class="ma-1"> C++ </v-chip>
              <v-chip class="ma-1"> Java </v-chip>
              <v-chip class="ma-1"> Software Desgin Patterns </v-chip>
              <v-chip class="ma-1"> Scrum </v-chip>
            </div>
          </v-card-text>
        </v-card>
      </v-timeline-item>
    </v-timeline>
  </div>
</template>

<script>
export default {
  name: "ProjectTimeline",
};
</script>

<style scoped></style>
