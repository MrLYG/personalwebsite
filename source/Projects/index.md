---
title: Projects
date: 2023-10-14 00:45:26
academia: true
---

<style>
    .projects-table {
        width: 100%;
        border-collapse: collapse;
        margin: 0 0;
    }
    .projects-table td {
        border: 0;
        vertical-align: middle;
    }
    .projects-table img {
        max-width: 100px;
        height: 100px;
    }
     .projects-table .paper p {
        text-align: left;
        margin: 0;
    }
    #techstack {
        font-size: 0.9em;
    }
</style>

<table class="projects-table">
      <tr>
        <td><img src="/img/ablator.png" alt="Abaltor"></td>
        <td class="paper">
                  <papertitle><b>ABLATOR: Robust Horizontal-Scaling of Machine Learning Ablation Experiments</b></papertitle>
                  <p id="techstack"><i >Python, MLOps, Docker, Github Action, Pytorch, Pytest</i></p>
                  <em>AutoML</em>, 2023
                  <br>
                  <a href="https://github.com/fostiropoulos/ablator"  style="color:blue;">Github</a>
                  /
                  <a href="https://openreview.net/pdf?id=eBLV3i7PG1c"  style="color:blue;">Paper</a>
                  <p></p></td>
      </tr>
      <tr style="margin-top:-200px;">
        <td class="paper" colspan="2">
                  <p>
                    <li>Contributed to "Ablator," an open-source Deep Learning framework used by 30+ USC researchers for horizontal scaling of ablation experiments and hyperparameter tuning, encompassing 70 pull requests.</li>
                      <li>Set up a CI pipeline with GitHub Actions, wrote docs and tests using Pytest, and achieved 95%+ coverage.</li>
                      <li>Created and published a Python API package for RClone on PyPI, simplifying cross-platform use without pre-installation and with automatic binary selection. (
                      <a href="https://github.com/MrLYG/python-rclone"  style="color:blue;">link</a>)</li>
                  </p>
                </td>
    </tr>
    <tr>
      <td colspan="2"><br><hr><br></td>
    </tr>
    <tr>
        <td><img src="/img/rocketmq.png" alt="RocketMq Operator"></td>
         <td class="paper">
                  <papertitle><b>RocketMqOperator: Auto Mangane RocketMq Cluster Instance on an Cloud Platform</b></papertitle><br>
                  <p id="techstack"><i >Kubernetes, Docker, Go, CI/CD, CRD, Operator-SDK, Helm3, Prometheus, Grafana</i></p>
                  <em>SenseTime (The first listed AI company in China)</em>, 2022-2023<br>
                  <a href="https://youtu.be/ZPjd3liwSkE" style="color:blue;">Video Introduction</a>
                  <p></p></td>
      </tr>
      <tr style="margin-top:-200px;">
        <td class="paper" colspan="2">
                  <p>
                      <li>Developed "RocketMQ as a Service", akin to "RabbitMQ as a Service" in AWS Marketplace, offering fully managed RocketMQ clusters in SaaS Platform, which resulted in a 100% increase in RocketMQ service creation speed.</li>
                      <li>Utilized Operator SDK to construct a Kubernetes-based RocketMQ Operator and Custom Resource Definitions (CRD), automating lifecycle management and reducing manual intervention.</li>
                      <li>Employed Helm3 to package components into Helm charts, simplifying Kubernetes deployment and improving resource management for the RocketMQ Operator project.</li>
                      <li>Integrated Prometheus and Grafana for real-time monitoring of key metrics and node health of the RocketMQ service.</li>
                      <li>Automated workflows including unit tests, image builds, and Helm3 Chart updates via GitLab CI/CD.</li>
                  </p>
                </td>
    </tr>
    <tr>
      <td colspan="2"><br><hr><br></td>
    </tr>
    <tr>
        <td><img src="/img/autotest.png" alt="AutoTest"></td>
         <td class="paper">
                  <papertitle><b>Web application cross-browser compatibility automatic testing tool based on record/replay</b></papertitle>
                  <p id="techstack"><i>Docker, Node.js, JSON, Vue.js, RobotFramework</i></p>
                  <em>Chinese Academy of Sciences (Top Research Institute)</em>, 2021-2022
                  <p></p>
      </tr>
      <tr style="margin-top:-200px;">
        <td class="paper" colspan="2">
                  <p>
                      <li>Participated in the R&D of a web-based automated testing tool employing Record and Playback technology. This tool allowed the recording, editing, execution, analysis, and result generation of user actions within test cases.</li>
                      <li>Using Node.js, transformed user actions recorded in JSON into Robot Framework scripts, achieving a 95% operation conversion coverage rate, to facilitate Playback testing.</li>
                      <li>Containerized the program with Docker and automated DevOps pipeline for development efficiency improvement</li>
                      <li>Employed Vue.js and AceEditor to fabricate custom components and layouts, enhancing front-end usability.</li>
                      <li>The implementation of the tool saves 15+ hours per week and improves end-to-end testing efficiency by 300%.</li>
                  </p>
                </td>
    </tr>
    <tr>
      <td colspan="2"><br><hr><br></td>
    </tr>
    <tr>
        <td><img src="/img/EventMaster.png" alt="EventMaster"></td>
         <td class="paper">
                  <papertitle><b>EventMaster</b></papertitle>
                  <br>
                  <p id="techstack"><i >Full Stack Website, Node.js, AngularJS, GCP, AJAX</i></p>
                  <em>USC CSCI571</em>, 2023<br>
                  <a href="https://github.com/MrLYG/MrLYG.github.io/tree/master/csci571/hw6"  style="color:blue;">Github</a>
                  <p></p>
      </tr>
      <tr style="margin-top:-200px;">
        <td class="paper" colspan="2">
                  <p>
                      <li>Developed a full-stack event search platform using JavaScript/Node.js, Express, AngularJS, TypeScript, and Bootstrap, aggregating event information and enhancing user interaction.</li>
                      <li>Integrated APIs such as Ticketmaster, Spotify, Google Maps, and social media to enrich data display on the frontend.</li>
                      <li>Deployed the project on the Google Cloud Platform(App Engine) with performance optimization.</li>
                  </p>
                </td>
    </tr>
    <tr>
      <td colspan="2"><br><hr><br></td>
    </tr>
    <tr>
         <td><img src="/img/CollegeAnalysis.png" alt="CollegeAnalysis"></td>
         <td class="paper">
                  <papertitle><b>College professional development analysis platform</b></papertitle>
                   <br>
                   <p id="techstack"><i >Full Stack Website, Web crawler, Python, MongoDB, MySQL, Java, Spring, Spring MVC, MyBatis, React, Docker</i></p>
                  <em> National-level Innovation Training Program -
                  <a href="http://bjcxcy.bjtu.edu.cn/Index/ItemDetail?id=3528e362-295d-4052-8f6a-4f0348313d50&_pageIndex=3595&_amp;_pageIndex=152&_eqid=8f8936dd0001b17200000003646f0237" style="color:blue;">link</a></em>, 2019<br>
                  </p>
                  <p></p>
      </tr>
      <tr style="margin-top:-200px;">
        <td class="paper" colspan="2">
                  <p>
                      <li>Led a team to collect and analyze job recruitment data using Web crawler and Python libraries, aiding university major and curriculum planning.</li>
                      <li>Stored data using MongoDB and MySQL databases for subsequent data processing and analysis.</li>
                      <li>Built data visualization interfaces using Spring and React technologies, improving data readability.</li>
                      <li>Used Docker for containerization and CI/CD technologies for automated operations, enhancing the efficiency of project deployment and operation, and ensuring project stability and reliability. </li>
                      <li>Achieved recognition as a "National Level Innovative Excellence Project for College Students" and adopted by school for professional development data support.</li>
                  </p>
                </td>
    </tr>
</table>
