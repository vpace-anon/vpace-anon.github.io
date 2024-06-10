---
layout: minimal
title: VPACE for Learning without Rewards or Demonstrations (CoRL 2024) -- Alternate
subtitle:  Value-Penalized Auxiliary Control from Examples for Learning without Rewards or Demonstrations
description: CoRL Submission on Learning from examples (i.e. no rewards or full-trajectory demonstrations) using value-penalization and auxiliary control.
nav_exclude: true
---

# Value-Penalized Auxiliary Control from Examples **(VPACE)** for Learning without Rewards or Demonstrations
{: .no_toc }

[<i class="fa fa-github" aria-hidden="true"></i> Github](https://github.com/vpace-anon/vpace){: .btn .btn-green }

### Anonymous Author(s)<sup>1</sup>
{: .no_toc }

<h5> 
    <i>
        <sup>1</sup>Affiliation
    </i>
</h5>

#### Submitted to Conference on Robot Learning (CoRL) 2024
{: .no_toc }

---

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

## Real Panda Results

### Exploratory Episodes over Time

#### Door

<div style='text-align:center'>
    <video width='100%' autoplay loop muted>
        <source src='/assets/vpace/big_vids/realdoor-exploration-crf23.mp4' type='video/mp4'>
        Your browser does not support the video tag.
    </video>
</div>

#### Drawer

<div style='text-align:center'>
    <video width='100%' autoplay loop muted>
        <source src='/assets/vpace/big_vids/realdrawer-exploration-crf23.mp4' type='video/mp4'>
        Your browser does not support the video tag.
    </video>
</div>

### Success Examples for Training

<div style='text-align:center'>
    <video width='100%' autoplay loop muted>
        <source src='/assets/vpace/big_vids/all_real_success_examples.mp4' type='video/mp4'>
        Your browser does not support the video tag.
    </video>
</div>

### Final Performance

<div style='text-align:center'>
    <video width='100%' autoplay loop muted>
        <source src='/assets/vpace/big_vids/real-finalperf-crf23.mp4' type='video/mp4'>
        Your browser does not support the video tag.
    </video>
</div>

## Simulation Results

### Exploratory Episodes over Time

#### Unstack-Stack

<div style='text-align:center'>
    <video width='100%' autoplay loop muted>
        <source src='/assets/vpace/big_vids/unstack-stack-exploration.mp4' type='video/mp4'>
        Your browser does not support the video tag.
    </video>
</div>

#### Insert

<div style='text-align:center'>
    <video width='100%' autoplay loop muted>
        <source src='/assets/vpace/big_vids/insert-exploration.mp4' type='video/mp4'>
        Your browser does not support the video tag.
    </video>
</div>

#### sawyer_drawer_open

<div style='text-align:center'>
    <video width='100%' autoplay loop muted>
        <source src='/assets/vpace/big_vids/drawer-open-exploration.mp4' type='video/mp4'>
        Your browser does not support the video tag.
    </video>
</div>

#### sawyer_box_close

<div style='text-align:center'>
    <video width='100%' autoplay loop muted>
        <source src='/assets/vpace/big_vids/box-close-exploration.mp4' type='video/mp4'>
        Your browser does not support the video tag.
    </video>
</div>

#### sawyer_bin_picking

<div style='text-align:center'>
    <video width='100%' autoplay loop muted>
        <source src='/assets/vpace/big_vids/bin-picking-exploration.mp4' type='video/mp4'>
        Your browser does not support the video tag.
    </video>
</div>

#### hammer-human-v0-dp

<div style='text-align:center'>
    <video width='100%' autoplay loop muted>
        <source src='/assets/vpace/big_vids/hammer-exploration.mp4' type='video/mp4'>
        Your browser does not support the video tag.
    </video>
</div>

#### relocate-human-v0-najp-dp

<div style='text-align:center'>
    <video width='100%' autoplay loop muted>
        <source src='/assets/vpace/big_vids/relocate-exploration.mp4' type='video/mp4'>
        Your browser does not support the video tag.
    </video>
</div>

### Success Examples for Training
The numerical state data corresponding to these example success images was the only signal (i.e., no reward function and no full trajectories) used for training policies in this work.
We also show examples from the initial state distributions.

#### Panda Tasks

<div style='text-align:center'>
    <video width='100%' autoplay loop muted>
        <source src='/assets/vpace/big_vids/all_panda_success_examples.mp4' type='video/mp4'>
        Your browser does not support the video tag.
    </video>
</div>

#### Sawyer Tasks

<div style='text-align:center'>
    <video width='100%' autoplay loop muted>
        <source src='/assets/vpace/big_vids/all_sawyer_success_examples.mp4' type='video/mp4'>
        Your browser does not support the video tag.
    </video>
</div>

#### Adroit Hand Tasks
The same data was used for the original and the delta-position variants.

<div style='text-align:center'>
    <video width='100%' autoplay loop muted>
        <source src='/assets/vpace/big_vids/all_hand_success_examples.mp4' type='video/mp4'>
        Your browser does not support the video tag.
    </video>
</div>

### Final Performance (All Tasks)

#### Panda Tasks

<div style='text-align:center'>
    <video width='100%' autoplay loop muted>
        <source src='/assets/vpace/big_vids/panda-finalperf-crf23.mp4' type='video/mp4'>
        Your browser does not support the video tag.
    </video>
</div>

#### Sawyer Tasks

<div style='text-align:center'>
    <video width='100%' autoplay loop muted>
        <source src='/assets/vpace/big_vids/sawyer-finalperf-crf23.mp4' type='video/mp4'>
        Your browser does not support the video tag.
    </video>
</div>

#### Adroit Hand Tasks

<div style='text-align:center'>
    <video width='100%' autoplay loop muted>
        <source src='/assets/vpace/big_vids/hand-finalperf-crf23.mp4' type='video/mp4'>
        Your browser does not support the video tag.
    </video>
</div>