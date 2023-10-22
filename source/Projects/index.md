---
title: Projects
date: 2023-10-14 00:45:26
academia: true
---

<style>
    .projects-table {
        width: 100%;
        border-collapse: collapse;
        margin: 0 auto;
    }
    .projects-table td {
        border: 0;

        vertical-align: middle;
    }
    .projects-table img {
        max-width: 200px;
        height: auto;
        margin-right: 20px;
    }
     .projects-table .paper p {
        text-align: left;
        margin: 0;
    }
</style>

<table class="projects-table">
    <tr>
        <td><img src="/img/ablator.png" alt="Abaltor"></td>
        <td class="paper">
                  <br>
                  <papertitle><b>ABLATOR: Robust Horizontal-Scaling of Machine Learning Ablation Experiments</b></papertitle><br><br>
                  <em>AutoML</em>, 2023
                  <br>
                  <a href="https://github.com/fostiropoulos/ablator">project page</a>
                  /
                  <a href="./data/ablator.pdf">paper</a>
                  <p></p>
                  <p>
                    Ablation experiments are important in improving Machine Learning (ML) models, where multiple
                    experimental trials are required for each component of a ML model. We find lack of available tools
                    and frameworks for horizontal scaling of ML experiments where manual effort is required that often
                    lead to errors. We propose a statefull experiment design framework, ABLATOR, that can scale a single
                    experiment to thousands of trials while being fault-tollerant and robust to errors. We performed the
                    largest ablation experiment for tabular data on Transformer models to date, evaluating 2,337 models
                    in total. Finally, we open source ABLATOR;
                  </p>
                  <br>
                </td>
    </tr>
    <tr>
        <td><img src="/img/rocketmq.png" alt="RocketMq Operator"></td>
        <td class="paper">
                  <br>
                  <papertitle><b>RocketMqOperator: Auto Mangane RocketMq Cluster Instance on an Cloud Platform</b></papertitle>
                  <br><br>
                  <a href="https://youtu.be/ZPjd3liwSkE" style="color:blue;">project video introduction</a>
                  <p></p>
                  <p>
                    The RocketMQ Operator automatically deploys and manages RocketMQ clusters on the Kubernetes-based cloud environment. RocketMQ is a popular distributed messaging and streaming platform with low latency, high performance and reliability, trillion-level capacity, and flexible scalability.
                  </p>
                  <p>· Horizontal Scaling - Safely and seamlessly scale up each component of RocketMQ.
                  </p>
                  <p>· Rolling Update - Gracefully perform rolling updates in order with no downtime.
                  </p>
                  <p>· Multi-cluster Support - Users can deploy and manage multiple RocketMQ name server clusters and broker clusters on a single Kubernetes cluster using RocketMQ Operator.
                  </p>
                  <p>· Topic Transfer - Operator can automatically migrate a specific topic from a source broker cluster to a target cluster without affecting the business.
                  </p>
                  <br>
                </td>
    </tr>
    <tr>
        <td><img src="/img/autotest.png" alt="AutoTest"></td>
        <td class="paper">
                  <br>
                  <papertitle><b>Web application cross-browser compatibility automatic testing tool based on record/replay</b></papertitle>
                  <br><br>
                  <p></p>
                  <p>
                    This is a web-based automated testing tool that utilizes Record and Playback technology. The tool allows for the recording, editing, execution, analysis, and result generation of user actions within test cases. It uses Node.js to convert user actions recorded in JSON to Robot Framework scripts, achieving a 95% operation conversion coverage rate for Playback testing. The program is containerized with Docker and has an automated DevOps pipeline for enhanced development efficiency. Additionally, Vue.js and AceEditor are employed to craft custom components and layouts, improving front-end usability.
                  </p>
                  <br>
                </td>
    </tr>
    <tr>
    <td><img src="/img/EventMaster.png" alt="EventMaster"></td>
        <td class="paper">
                  <br>
                  <papertitle><b>EventMaster</b></papertitle>
                  <br><br>
                  <p></p>
                  <p>
                    EventMaster is an event search platform that aggregates event
information from all around the United States. The project allows users to search for
upcoming events based on keywords, dates, and event types, as well as display detailed
information about related events. The project also features a bookmarking function, allowing
users to save their favorite events for easy access.
                  </p>
                  <br>
                </td>
    </tr>
    <tr>
    <td><img src="/img/CollegeAnalysis.png" alt="CollegeAnalysis"></td>
        <td class="paper">
                  <br>
                  <papertitle><b>College professional development analysis platform</b></papertitle>
                  <br><br>
                  <p>National-level Innovation Training Program -
                  <a href="http://bjcxcy.bjtu.edu.cn/Index/ItemDetail?id=3528e362-295d-4052-8f6a-4f0348313d50&_pageIndex=3595&_amp;_pageIndex=152&_eqid=8f8936dd0001b17200000003646f0237" style="color:blue;">link</a></p>
                  <br>
                  <p>
                    This project, which participated in the "Internet Innovation Competition,"
utilizes big data technology to gather information from recruitment websites and conduct
multi-dimensional statistical analysis, providing data support for college major development
and curriculum planning. And The project was awarded the "National College Student Innovation
Excellence Project";
                  </p>
                  <br>
                </td>
    </tr>
</table>
