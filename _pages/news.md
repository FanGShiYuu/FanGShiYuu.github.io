---
layout: archive
title: "News"
permalink: /news/
author_profile: true
---

<style>
.pub-block {
  margin-bottom: 28px;
  padding-bottom: 24px;
  border-bottom: 1px solid #eee;
}
.pub-title {
  margin-bottom: 10px;
  font-size: 1em;
  line-height: 1.5;
}
.pub-title a {
  font-weight: bold;
  text-decoration: none;
  color: inherit;
}
.pub-title a:hover {
  text-decoration: underline;
  color: inherit;
  opacity: 0.75;
}
.pub-title-nolink {
  margin-bottom: 10px;
  font-size: 1em;
  line-height: 1.5;
  font-weight: bold;
}
.pub-entry {
  display: flex;
  align-items: flex-start;
  gap: 20px;
}
.pub-img {
  flex: 0 0 43%;
  max-width: 43%;
}
.pub-img img {
  width: 100%;
  height: auto;
  border-radius: 4px;
  object-fit: cover;
}
.pub-info {
  flex: 1;
}
.pub-info p {
  margin: 4px 0;
  line-height: 1.6;
}
.pub-abstract {
  margin-top: 8px !important;
  line-height: 1.6;
}
h2 {
  margin-top: 32px;
  margin-bottom: 16px;
}
</style>

This page shares some of our latest work. Click the publication title to view the article. We sincerely welcome your comments.

## Multi-Vehicle Cooperative Decision

<div class="pub-block">
  <p class="pub-title"><a href="https://papers.ssrn.com/sol3/papers.cfm?abstract_id=6297834">Game in Graph: Distributed Cooperative Decision-Making Framework for Multi-Level Equilibrium in Mixed Traffic.</a></p>
  <div class="pub-entry">
    <div class="pub-img"><img src="../images/GIG.png" alt="GIG"></div>
    <div class="pub-info">
      <p><strong><em>Shiyu Fang</em></strong>, Bing Zhu, Peng Hang, Chen Lv, Jian Sun*.</p>
      <p class="pub-abstract"><strong>Abstract:</strong> This paper proposes the Game in Graph (GIG) framework for cooperative decision-making. Traffic scenarios are modeled as a Spatiotemporal Conflict Topological Graph (SCTG) with heuristic-refined edges. The global graph is partitioned into high-conflict subgraphs via modularity maximization to enable distributed optimization. A bottom-up system utility is then decomposed across subgraphs, achieving multi-level equilibrium among vehicles, subgroups, and the overall system. </p>
    </div>
  </div>
</div>

<div class="pub-block">
  <p class="pub-title-nolink">Toward Cooperative Driving in Mixed Traffic: An Adaptive Potential Game-Based Approach with Field Test Verification.</p>
  <div class="pub-entry">
    <div class="pub-img"><img src="../images/PG.png" alt="PG"></div>
    <div class="pub-info">
      <p><strong><em>Shiyu Fang</em></strong>, Xiaocong Zhao, Xuekai Liu, Peng Hang*, Jianqiang Wang, Yunpeng Wang, Jian Sun*.</p>
      <p class="pub-abstract"><strong>Abstract:</strong> This paper proposes an adaptive potential game (APG)–based cooperative driving framework. A system utility function is constructed from a general individual utility form to jointly optimize individual and system objectives. The Lloyd Shapley value is adopted to quantify each vehicle’s marginal contribution. Moreover, HDV preference estimation is iteratively refined by comparing observed behaviors with APG-predicted actions, enhancing overall safety and efficiency. </p>
    </div>
  </div>
</div>

## Single-Vehicle Interactive Decision

<div class="pub-block">
  <p class="pub-title"><a href="https://www.researchgate.net/publication/395709363_CoReVLA_A_Dual-Stage_End-to-End_Autonomous_Driving_Framework_for_Long-Tail_Scenarios_via_Collect-and-Refine">CoReVLA: A Dual-Stage End-to-End Autonomous Driving Framework for Long-Tail Scenarios via Collect-and-Refine.</a></p>
  <div class="pub-entry">
    <div class="pub-img"><img src="../images/CoReVLA.png" alt="CoReVLA"></div>
    <div class="pub-info">
      <p><strong><em>Shiyu Fang</em></strong>, Yiming Cui, Haoyang Liang, Chen Lv, Peng Hang*, Jian Sun.</p>
      <p class="pub-abstract"><strong>Abstract:</strong> CoReVLA is a continual end-to-end driving framework targeting long-tail scenarios. It is first fine-tuned on mixed driving QA datasets, then deployed in the Transportation Cave Automatic Virtual Environment (TransCAVE) to collect driver takeover data as failure signals. Finally, Direct Preference Optimization (DPO) refines the model using human preferences, avoiding reward hacking.</p>
    </div>
  </div>
</div>
