# About
Here are my talks, blog posts and other related links.

# Elad Leev
<p align='center'>
<img src="img/elad-round.png" width="100"><br>
</p>

<p align='center'>
  <a href="https://www.linkedin.com/in/eladleev/">
    <img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>&nbsp;&nbsp;
    <a href="https://medium.com/@eladleev">
    <img src="https://img.shields.io/badge/medium-%2312100E.svg?&style=for-the-badge&logo=medium&logoColor=white" />
  </a>&nbsp;&nbsp;
  </a>
    <a href="https://stackoverflow.com/users/3922514/elad-leev">
    <img src="https://img.shields.io/badge/stackoverflow-%23FE7A16.svg?&style=for-the-badge&logo=stackoverflow&logoColor=white" />
  </a>&nbsp;&nbsp;
</p>
<p align='center'>
    <a href="https://twitter.com/Eladleev">
    <img src="https://img.shields.io/badge/twitter-follow%20me-%231DA1F2.svg?&style=for-the-badge&logo=twitter" />
  </a>
</p>

Data engineer with strong experience managing complex production operations, with expertise in distributed systems and databases.<br>
Elad likes to solve complex problems around delivering real time infrastructure in perpetual growth, and maintains some of the core pieces of large-scale production architecture serving 200B+ events daily.<br>
Some of the technologies Elad works with include Kafka, Aerospike, Redis, Memcached, and he likes to program in Python, Ruby and Go.
</p>

## &#187;	 Talk Recordings
&#183; [Kafka: Revolution to Evolution](https://www.youtube.com/watch?v=OQwK0n0x65o) - DataOps Meetup: Conquering Data with Kafka & Airflow <sub>[Heb] [2020] [Full]</sub> <br>
&#183; [Kafka Lag Monitoring For Human Beings](https://www.confluent.io/resources/kafka-summit-2020/kafka-lag-monitoring-for-human-beings) - Kafka Summit 2020 <sub>[Eng] [2020] [Full]</sub> <br>
&#183; [Handling Increasing Load and Reducing Costs During COVID-19 Crisis](https://www.youtube.com/watch?v=rRRTTxBohrg&t=1677s) <sub>[Heb] [2020] [10m]</sub> <br>
&#183; [Migrating from BitBucket to GitLab](https://www.youtube.com/watch?v=z_6tVRCyJxs) - GitlabCommit San Francisco 2020 <sub>[Eng] [2020] [Full] </sub><br>
&#183; [What can you learn from the biggest automation company in the world?](https://youtu.be/nlOgFPTwdq0) <sub>[Eng] [2019] [Ignite]</sub> <br>
&#183; [AppsFlyer's Case Study of GitLab](https://www.youtube.com/watch?v=N8pEKNw4nmI)  <sub>[Heb] [2018] [Full]</sub> <br>


## &#187;	 Blog Posts
&#183; [A Practical Guide for Kafka Cost Reduction](https://leevs.dev/kafka-cost-reduction/)<br>
&#183; [Apache Kafka Lag Monitoring at AppsFlyer](https://www.confluent.io/blog/kafka-lag-monitoring-and-metrics-at-appsflyer/)<br>
&#183; [My journey from Python to Go](https://medium.com/appsflyer/my-journey-from-python-to-go-3859783c6b3c)<br>
&#183; [GitLab: The Magic of System Hooks](https://medium.com/appsflyer/gitlab-the-magic-of-system-hooks-f38c4f7ca8e7)<br>
&#183; Personal Blog - [Heb](https://leev.tech/) / [Eng](https://leevs.dev/) <br>

## &#187;	 Translated Blog Posts
&#183; My journey from Python to Go [[Chinese - InfoQ]](https://www.infoq.cn/article/G-cfduQWKy3ROfx5p6US), [[Russian - Habr]](https://habr.com/ru/company/skillbox/blog/444866/)

&#183; A Practical Guide for Kafka Cost Reduction [[Chinese - InfoQ]](https://www.infoq.cn/article/zGb2m6e17hlmRDxViaNi)

## &#187;	 Related links
&#183; [Apache Kafka Lag Monitoring at AppsFlyer](https://www.confluent.io/blog/kafka-lag-monitoring-and-metrics-at-appsflyer/) - Confluent Blog [Eng]<br>
&#183; [Best Kafka Summit Videos](http://kafka.apache.org/videos#kafka_operations:~:text=Kafka%20Lag%20Monitoring%20For%2[…]an%20Beings%2C%20Elad%20Leev%20(AppsFlyer)%2C%20KS%202020) - Apache Kafka Official Page [Eng]<br>
&#183; [What is the company doing “Flying” the Apps?](https://www.aerospike.com/news/news-article/what-is-the-company-doing-flying-the-apps/) - Aerospike Blog [Eng]<br>
&#183; [How AppsFlyer use Aerospike to support the growth during COVID-19](https://www.pc.co.il/thenewcom/315643/) - People & Computers [Heb]<br>
&#183; [Why AppsFlyer moved from Bitbucket to GitLab](https://about.gitlab.com/blog/2020/04/27/appsflyer-moves-to-gitlab/) - Gitlab Blog<br>
&#183; [GitLab Heroes Page](https://about.gitlab.com/community/heroes/members) - Gitlab Website<br>

## &#187;	 Talks abstract
_Click to expand_

<details><summary><strong>Let’s make your CFO happy; A practical guide for cost reduction</strong></summary>

#### Talk Description
According to Gartner Forecasts, the worldwide end-user spending on public cloud services is forecast to grow by 23% in 2021, to a total of $332B. As organizations evolve and grow, data rates grow too, as do consequent cloud costs. Take a look at your AWS bill, and you will probably find Hadoop, Spark, and Kafka at the top. So what can we do?

In this talk, we are going to address exactly this problem. We will understand what we are paying for, how to develop an economic mindset, where we can cut costs, and what we can proactively do to reduce our cloud infrastructure cost.


<p><strong>Type:</strong> Full-length Presentation</p>
<p><strong>Tags:</strong> Cloud, Cloud Cost, FinOps, Kafka, Spark, Distributed Systems, Cost reduction, Cost saving, AWS, GCP, Data</p>
<hr/>
</details>

<details><summary><strong>Kafka Lag Monitoring for Human Beings</strong></summary>

#### Talk Description
One of the key metrics to monitor when working with Apache Kafka, as a data pipeline or a streaming platform, is Consumer Groups Lag.

Lag is the delta between the last produced message and the last committed message of a partition. In other words, lag indicates how far behind your application is in processing up-to-date information.
For a long time, we used our own service to keep track of these metrics, collect them and visualize them. But this didn’t scale well.

You had to perform many manual operations, redeploy it and to do other tedious manual tasks, but most importantly, the biggest gap for us, was that its out was represented in absolute numbers (e.g - your lag is 30K), which basically tells you nothing as a human being.

We understood that we had to find a more suitable solution that will give us better visibility and will allow us to measure the lag in a time-based format that we all understand.
In this talk, I’m going to go over the core concepts of Kafka offsets and lags, and explain why lag even matters and is an important KPI to measure.  I’ll also talk about the kind of research we did to find the right tool, what the options in the market were at the time, and eventually why we chose Linkedin’s Burrow as the right tool for us. And finally, I’ll take a closer look at Burrow, its building blocks, how we build and deploy it, how we monitor better with it, and eventually the most important improvement - how we transformed its output from numbers to time-based metrics.

<p><strong>Type</strong>: Full-length Presentation</p>
<p><strong>Tags</strong>: Kafka, Monitoring, Lag, Data Pipeline, Streaming, Burrow</p>
<hr/>
</details>


<details><summary><strong>A Journey from Python to Go</strong></summary>

#### Talk Description

I love Python. It has been my go-to language for the past five years. But the growth in the popularity and maturity of Go, alongside the strong user base, made me think about how I can add it into my tool set.

In this talk, I'm going to tell you about my journey from Python to Go, and provide you with some tips and expose you to some of the resources that helped me succeed on this journey and live to tell the tale.  I will dive into some of the main differences, and how to minimize the learning curve, as well as some of the excellent libraries and tools that enabled me to ramp up my Go coding skills pretty quickly & painlessly.

<p><strong>Type:</strong> Full-length Presentation</p>
<p><strong>Tags:</strong> Go, Golang, Python, Coding, Resources, Tips</p>
<hr/>
</details>

<details><summary><strong>What can you learn from the biggest automation company in the world?</strong></summary>

#### Talk Description
We will go over some high scale patterns in one of the most surprising and loved company in the industry.<br>
I'm lovin it.


<p><strong>Type</strong>: Ignite</p>
<p><strong>Tags</strong>: Tech, Scale, Software Patterns, System Design, Distributed Systems</p>
<hr/>
</details>


<details><summary><strong>Migration from BitBucket to GitLab</strong></summary>

#### Talk Description
AppsFlyer migrated its entire git operation, with production clients from BitBucket to Gitlab.  This talk will dive into what was involved with the migration process - from building the architecture through selecting the tooling and eventually how we built our very own self-serve API abstraction over the GitLab API.  Some of the points the talk will review:
* The migration process - from Mercurial to Git, how to move all projects, how to get developer buy-in and the lessons learned during the process
* Architecture - How we built it, the challenges we faced, how we built our DR solution, alongside the distributed backup  
* Building monitoring for the environment
* Self-service, tooling & and some pro tips and tricks for working with Gitlab

While this will be a talk about our Gitlab implementation, it will also provide key takeways for making such a migration in a large-scale engineering organization.

<p><strong>Type</strong>: Full-length Presentation</p>
<p><strong>Tags</strong>: GitLab, Git, BitBucket, Migration, Mercurial, hg, API</p>
<hr/>
</details>
