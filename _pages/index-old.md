---
layout: minimal
title: VPACE for Learning without Rewards or Demonstrations (CoRL 2024)
subtitle: Value-Penalized Auxiliary Control from Examples for Learning without Rewards or Demonstrations
description: CoRL Submission on Learning from examples (i.e. no rewards or full-trajectory demonstrations) using value-penalization and auxiliary control.
permalink: /individual-videos/
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
{::nomarkdown}
<div style='text-align:center'>
    <table>
        <tr>
            <!-- <td style="width: 12px; min-width:10px"></td> -->
            <td style="width: 40px; min-width:38px"></td>
            <td> <font size="+1"> <b>VPACE</b> </font> </td>
            <td> SQIL </td>
            <!-- <td> <font size="+1"> <b>VPACE</b> </font> (timelapse) </td>
            <td> SQIL (timelapse) </td> -->
        </tr>
        <tr>
            <td style="width: 40px; min-width: 38px; max-width: 60px">
                <!-- <div style=" transform: rotate(-90deg); white-space: nowrap"> -->
                <div style=" transform: rotate(-90deg); width: 100px; height: 100px">
                    40 minutes
                </div>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/real/door/multi-sqil/10k-exp-120120-1x.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/real/door/sqil/10k-exp-1x.mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
        </tr>
        <tr>
            <td style="width: 40px; min-width: 38px; max-width: 60px">
                <!-- <div style=" transform: rotate(-90deg); white-space: nowrap"> -->
                <div style=" transform: rotate(-90deg); width: 100px; height: 100px">
                    40 minutes (timelapse)
                </div>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/real/door/multi-sqil/10k-explore-timelapse.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/real/door/sqil/10k-explore-timelapse.mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
        </tr>
        <tr>
            <td style="width: 40px; min-width: 38px; max-width: 60px">
                <!-- <div style=" transform: rotate(-90deg); white-space: nowrap"> -->
                <div style=" transform: rotate(-90deg); width: 100px; height: 100px">
                    120 minutes
                </div>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/real/door/multi-sqil/30k-exp-120120-1x.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/real/door/sqil/30k-exp-1x.mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
        </tr>
        <tr>
            <td style="width: 40px; min-width: 38px; max-width: 60px">
                <!-- <div style=" transform: rotate(-90deg); white-space: nowrap"> -->
                <div style=" transform: rotate(-90deg); width: 100px; height: 100px">
                    120 minutes (timelapse)
                </div>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/real/door/multi-sqil/30k-explore-timelapse.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/real/door/sqil/30k-explore-timelapse.mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
        </tr>
        <tr>
            <td style="width: 40px; min-width: 38px; max-width: 60px">
                <!-- <div style=" transform: rotate(-90deg); white-space: nowrap"> -->
                <div style=" transform: rotate(-90deg); width: 100px; height: 100px">
                    200 minutes
                </div>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/real/door/multi-sqil/50k-exp-120120-1x.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/real/door/sqil/50k-exp-1x.mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
        </tr>
        <tr>
            <td style="width: 40px; min-width: 38px; max-width: 60px">
                <!-- <div style=" transform: rotate(-90deg); white-space: nowrap"> -->
                <div style=" transform: rotate(-90deg); width: 100px; height: 100px">
                    200 minutes (timelapse)
                </div>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/real/door/multi-sqil/50k-explore-timelapse.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/real/door/sqil/50k-explore-timelapse.mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
        </tr>
    </table>
</div>
{:/}

#### Drawer
{::nomarkdown}
<div style='text-align:center'>
    <table>
        <tr>
            <!-- <td style="width: 12px; min-width:10px"></td> -->
            <td style="width: 40px; min-width:38px"></td>
            <td> <font size="+1"> <b>VPACE</b> </font> </td>
            <td> SQIL </td>
            <!-- <td> <font size="+1"> <b>VPACE</b> </font> (timelapse) </td>
            <td> SQIL (timelapse) </td> -->
        </tr>
        <tr>
            <td style="width: 40px; min-width: 38px; max-width: 60px">
                <!-- <div style=" transform: rotate(-90deg); white-space: nowrap"> -->
                <div style=" transform: rotate(-90deg); width: 100px; height: 100px">
                    20 minutes
                </div>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/real/drawer/multi-sqil/5k-exp-120120-1x.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/real/drawer/sqil/5k-exp-1x.mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
        </tr>
        <tr>
            <td style="width: 40px; min-width: 38px; max-width: 60px">
                <!-- <div style=" transform: rotate(-90deg); white-space: nowrap"> -->
                <div style=" transform: rotate(-90deg); width: 100px; height: 100px">
                    20 minutes (timelapse)
                </div>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/real/drawer/multi-sqil/5k-explore-timelapse.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/real/drawer/sqil/5k-explore-timelapse.mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
        </tr>
        <tr>
            <td style="width: 40px; min-width: 38px; max-width: 60px">
                <!-- <div style=" transform: rotate(-90deg); white-space: nowrap"> -->
                <div style=" transform: rotate(-90deg); width: 100px; height: 100px">
                    60 minutes
                </div>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/real/drawer/multi-sqil/15k-exp-120120-1x.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/real/drawer/sqil/15k-exp-1x.mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
        </tr>
        <tr>
            <td style="width: 40px; min-width: 38px; max-width: 60px">
                <!-- <div style=" transform: rotate(-90deg); white-space: nowrap"> -->
                <div style=" transform: rotate(-90deg); width: 100px; height: 100px">
                    60 minutes (timelapse)
                </div>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/real/drawer/multi-sqil/15k-explore-timelapse.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/real/drawer/sqil/15k-explore-timelapse.mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
        </tr>
        <tr>
            <td style="width: 40px; min-width: 38px; max-width: 60px">
                <!-- <div style=" transform: rotate(-90deg); white-space: nowrap"> -->
                <div style=" transform: rotate(-90deg); width: 100px; height: 100px">
                    100 minutes
                </div>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/real/drawer/multi-sqil/25k-exp-120120-1x.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/real/drawer/sqil/25k-exp-1x.mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
        </tr>
        <tr>
            <td style="width: 40px; min-width: 38px; max-width: 60px">
                <!-- <div style=" transform: rotate(-90deg); white-space: nowrap"> -->
                <div style=" transform: rotate(-90deg); width: 100px; height: 100px">
                    100 minutes (timelapse)
                </div>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/real/drawer/multi-sqil/25k-explore-timelapse.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/real/drawer/sqil/25k-explore-timelapse.mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
        </tr>
    </table>
</div>
{:/}

### Success Examples for Training
The numerical state data corresponding to these example success images was the only signal (i.e., no reward function and no full trajectories) used for training policies in this work.
We also show examples from the initial state distributions.

{::nomarkdown}
<div style='text-align:center'>
    <table>
        <tr>
            <!-- <td style="width: 12px; min-width:10px"></td> -->
            <td style="width: 10px; min-width:8px"></td>
            <td> Initial State </td>
            <td> Reach </td>
            <td> Grasp </td>
            <td> Main </td>
        </tr>
        <tr>
            <td style="width: 10px; min-width: 8px; max-width: 40px">
                <!-- <div style=" transform: rotate(-90deg); white-space: nowrap"> -->
                <div style=" transform: rotate(-90deg); width: 100px; height: 100px">
                    Real Door
                </div>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/real_reset_success_examples/PandaDoorNoJamAngle-reset.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/real_reset_success_examples/PandaDoorNoJamAngle-reach-suc.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/real_reset_success_examples/PandaDoorNoJamAngle-grasp-suc.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/real_reset_success_examples/PandaDoorNoJamAngle-suc.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
        </tr>
        <tr>
            <td style="width: 10px; min-width: 8px; max-width: 40px">
                <!-- <div style=" transform: rotate(-90deg); white-space: nowrap"> -->
                <div style=" transform: rotate(-90deg); width: 100px; height: 100px">
                    Real Drawer
                </div>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/real_reset_success_examples/PandaDrawerLine-reset.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/real_reset_success_examples/PandaDrawerLine-reach-suc.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/real_reset_success_examples/PandaDrawerLine-grasp-suc.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/real_reset_success_examples/PandaDrawerLine-suc.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
        </tr>
    </table>
</div>
{:/}

### Final Performance
{::nomarkdown} 
<div style='text-align:center'>
    <table>
        <tr>
            <!-- <td style="width: 12px; min-width:10px"></td> -->
            <td style="width: 10px; min-width:8px"></td>
            <td> <font size="+1"> <b>VPACE</b> </font> </td>
            <td> SQIL </td>
        </tr>
        <tr>
            <td style="width: 10px; min-width: 8px; max-width: 40px">
                <!-- <div style=" transform: rotate(-90deg); white-space: nowrap"> -->
                <div style=" transform: rotate(-90deg); width: 100px; height: 100px">
                    Real Door
                </div>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/real/door/multi-sqil/50k-eval-1x.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/real/door/sqil/50k-eval-1x.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
        </tr>
        <tr>
            <td style="width: 10px; min-width: 8px; max-width: 40px">
                <!-- <div style=" transform: rotate(-90deg); white-space: nowrap"> -->
                <div style=" transform: rotate(-90deg); width: 100px; height: 100px">
                    Real Drawer
                </div>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/real/drawer/multi-sqil/25k-eval-1x.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/real/drawer/sqil/25k-eval-1x.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
        </tr>
    </table>
</div>
{:/}

## Simulation Results

### Exploratory Episodes over Time

#### Unstack-Stack
{::nomarkdown}
<div style='text-align:center'>
    <table>
        <tr>
            <!-- <td style="width: 12px; min-width:10px"></td> -->
            <td style="width: 10px; min-width:8px"></td>
            <td> <font size="+1"> <b>VPACE</b> </font> </td>
            <td> SQIL </td>
            <td> RCE </td>
            <td> DAC </td>
        </tr>
        <tr>
            <td style="width: 10px; min-width: 8px; max-width: 40px">
                <!-- <div style=" transform: rotate(-90deg); white-space: nowrap"> -->
                <div style=" transform: rotate(-90deg); width: 100px; height: 100px">
                    100k steps
                </div>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/unstack_stack_env_only_no_move_0/multi-sqil/02_eps_2-0x_sto_100000steps.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/unstack_stack_env_only_no_move_0/sqil-no-vp/02_eps_2-0x_sto_100000steps.mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/unstack_stack_env_only_no_move_0/rce/02_eps_2-0x_sto_100000steps.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/unstack_stack_env_only_no_move_0/disc/02_eps_2-0x_sto_100000steps.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
        </tr>
        <tr>
            <td style="width: 10px; min-width: 8px; max-width: 40px">
                <!-- <div style=" transform: rotate(-90deg); white-space: nowrap"> -->
                <div style=" transform: rotate(-90deg); width: 100px; height: 100px">
                    200k steps
                </div>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/unstack_stack_env_only_no_move_0/multi-sqil/02_eps_2-0x_sto_200000steps.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/unstack_stack_env_only_no_move_0/sqil-no-vp/02_eps_2-0x_sto_200000steps.mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/unstack_stack_env_only_no_move_0/rce/02_eps_2-0x_sto_200000steps.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/unstack_stack_env_only_no_move_0/disc/02_eps_2-0x_sto_200000steps.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
        </tr>   
        <tr>
            <td style="width: 10px; min-width: 8px; max-width: 40px">
                <!-- <div style=" transform: rotate(-90deg); white-space: nowrap"> -->
                <div style=" transform: rotate(-90deg); width: 100px; height: 100px">
                    300k steps
                </div>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/unstack_stack_env_only_no_move_0/multi-sqil/02_eps_2-0x_sto_300000steps.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/unstack_stack_env_only_no_move_0/sqil-no-vp/02_eps_2-0x_sto_300000steps.mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/unstack_stack_env_only_no_move_0/rce/02_eps_2-0x_sto_300000steps.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/unstack_stack_env_only_no_move_0/disc/02_eps_2-0x_sto_300000steps.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
        </tr>
    </table>
</div>
{:/}

#### Insert
{::nomarkdown}
<div style='text-align:center'>
    <table>
        <tr>
            <!-- <td style="width: 12px; min-width:10px"></td> -->
            <td style="width: 10px; min-width:8px"></td>
            <td> <font size="+1"> <b>VPACE</b> </font> </td>
            <td> SQIL </td>
            <td> RCE </td>
            <td> DAC </td>
        </tr>
        <tr>
            <td style="width: 10px; min-width: 8px; max-width: 40px">
                <!-- <div style=" transform: rotate(-90deg); white-space: nowrap"> -->
                <div style=" transform: rotate(-90deg); width: 100px; height: 100px">
                    100k steps
                </div>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/insert_no_bring_no_move_0/multi-sqil/02_eps_2-0x_sto_100000steps.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/insert_no_bring_no_move_0/sqil-no-vp/02_eps_2-0x_sto_100000steps.mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/insert_no_bring_no_move_0/rce/02_eps_2-0x_sto_100000steps.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/insert_no_bring_no_move_0/disc/02_eps_2-0x_sto_100000steps.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
        </tr>
        <tr>
            <td style="width: 10px; min-width: 8px; max-width: 40px">
                <!-- <div style=" transform: rotate(-90deg); white-space: nowrap"> -->
                <div style=" transform: rotate(-90deg); width: 100px; height: 100px">
                    200k steps
                </div>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/insert_no_bring_no_move_0/multi-sqil/02_eps_2-0x_sto_200000steps.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/insert_no_bring_no_move_0/sqil-no-vp/02_eps_2-0x_sto_200000steps.mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/insert_no_bring_no_move_0/rce/02_eps_2-0x_sto_200000steps.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/insert_no_bring_no_move_0/disc/02_eps_2-0x_sto_200000steps.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
        </tr>
        <tr>
            <td style="width: 10px; min-width: 8px; max-width: 40px">
                <!-- <div style=" transform: rotate(-90deg); white-space: nowrap"> -->
                <div style=" transform: rotate(-90deg); width: 100px; height: 100px">
                    300k steps
                </div>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/insert_no_bring_no_move_0/multi-sqil/02_eps_2-0x_sto_300000steps.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/insert_no_bring_no_move_0/sqil-no-vp/02_eps_2-0x_sto_300000steps.mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/insert_no_bring_no_move_0/rce/02_eps_2-0x_sto_300000steps.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/insert_no_bring_no_move_0/disc/02_eps_2-0x_sto_300000steps.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
        </tr>
    </table>
</div>
{:/}

#### sawyer_drawer_open
{::nomarkdown}
<div style='text-align:center'>
    <table>
        <tr>
            <!-- <td style="width: 12px; min-width:10px"></td> -->
            <td style="width: 10px; min-width:8px"></td>
            <td> <font size="+1"> <b>VPACE</b> </font> </td>
            <td> SQIL </td>
            <td> RCE </td>
            <td> DAC </td>
        </tr>
        <tr>
            <td style="width: 10px; min-width: 8px; max-width: 40px">
                <!-- <div style=" transform: rotate(-90deg); white-space: nowrap"> -->
                <div style=" transform: rotate(-90deg); width: 100px; height: 100px">
                    50k steps
                </div>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/sawyer_drawer_open/multi-sqil/02_eps_2-0x_sto_50000steps.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/sawyer_drawer_open/sqil-no-vp/02_eps_2-0x_sto_50000steps.mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/sawyer_drawer_open/rce/02_eps_2-0x_sto_50000steps.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/sawyer_drawer_open/disc/02_eps_2-0x_sto_50000steps.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
        </tr>
        <tr>
            <td style="width: 10px; min-width: 8px; max-width: 40px">
                <!-- <div style=" transform: rotate(-90deg); white-space: nowrap"> -->
                <div style=" transform: rotate(-90deg); width: 100px; height: 100px">
                    100k steps
                </div>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/sawyer_drawer_open/multi-sqil/02_eps_2-0x_sto_100000steps.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/sawyer_drawer_open/sqil-no-vp/02_eps_2-0x_sto_100000steps.mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/sawyer_drawer_open/rce/02_eps_2-0x_sto_100000steps.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/sawyer_drawer_open/disc/02_eps_2-0x_sto_100000steps.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
        </tr>
        <tr>
            <td style="width: 10px; min-width: 8px; max-width: 40px">
                <!-- <div style=" transform: rotate(-90deg); white-space: nowrap"> -->
                <div style=" transform: rotate(-90deg); width: 100px; height: 100px">
                    150k steps
                </div>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/sawyer_drawer_open/multi-sqil/02_eps_2-0x_sto_150000steps.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/sawyer_drawer_open/sqil-no-vp/02_eps_2-0x_sto_150000steps.mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/sawyer_drawer_open/rce/02_eps_2-0x_sto_150000steps.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/sawyer_drawer_open/disc/02_eps_2-0x_sto_150000steps.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
        </tr>
    </table>
</div>
{:/}

#### sawyer_box_close
{::nomarkdown}
<div style='text-align:center'>
    <table>
        <tr>
            <!-- <td style="width: 12px; min-width:10px"></td> -->
            <td style="width: 10px; min-width:8px"></td>
            <td> <font size="+1"> <b>VPACE</b> </font> </td>
            <td> SQIL </td>
            <td> RCE </td>
            <td> DAC </td>
        </tr>
        <tr>
            <td style="width: 10px; min-width: 8px; max-width: 40px">
                <!-- <div style=" transform: rotate(-90deg); white-space: nowrap"> -->
                <div style=" transform: rotate(-90deg); width: 100px; height: 100px">
                    50k steps
                </div>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/sawyer_box_close/multi-sqil/02_eps_2-0x_sto_50000steps.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/sawyer_box_close/sqil-no-vp/02_eps_2-0x_sto_50000steps.mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/sawyer_box_close/rce/02_eps_2-0x_sto_50000steps.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/sawyer_box_close/disc/02_eps_2-0x_sto_50000steps.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
        </tr>
        <tr>
            <td style="width: 10px; min-width: 8px; max-width: 40px">
                <!-- <div style=" transform: rotate(-90deg); white-space: nowrap"> -->
                <div style=" transform: rotate(-90deg); width: 100px; height: 100px">
                    100k steps
                </div>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/sawyer_box_close/multi-sqil/02_eps_2-0x_sto_100000steps.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/sawyer_box_close/sqil-no-vp/02_eps_2-0x_sto_100000steps.mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/sawyer_box_close/rce/02_eps_2-0x_sto_100000steps.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/sawyer_box_close/disc/02_eps_2-0x_sto_100000steps.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
        </tr>
        <tr>
            <td style="width: 10px; min-width: 8px; max-width: 40px">
                <!-- <div style=" transform: rotate(-90deg); white-space: nowrap"> -->
                <div style=" transform: rotate(-90deg); width: 100px; height: 100px">
                    150k steps
                </div>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/sawyer_box_close/multi-sqil/02_eps_2-0x_sto_150000steps.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/sawyer_box_close/sqil-no-vp/02_eps_2-0x_sto_150000steps.mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/sawyer_box_close/rce/02_eps_2-0x_sto_150000steps.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/sawyer_box_close/disc/02_eps_2-0x_sto_150000steps.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
        </tr>
    </table>
</div>
{:/}

#### sawyer_bin_picking
{::nomarkdown}
<div style='text-align:center'>
    <table>
        <tr>
            <!-- <td style="width: 12px; min-width:10px"></td> -->
            <td style="width: 10px; min-width:8px"></td>
            <td> <font size="+1"> <b>VPACE</b> </font> </td>
            <td> SQIL </td>
            <td> RCE </td>
            <td> DAC </td>
        </tr>
        <tr>
            <td style="width: 10px; min-width: 8px; max-width: 40px">
                <!-- <div style=" transform: rotate(-90deg); white-space: nowrap"> -->
                <div style=" transform: rotate(-90deg); width: 100px; height: 100px">
                    50k steps
                </div>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/sawyer_bin_picking/multi-sqil/02_eps_2-0x_sto_50000steps.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/sawyer_bin_picking/sqil-no-vp/02_eps_2-0x_sto_50000steps.mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/sawyer_bin_picking/rce/02_eps_2-0x_sto_50000steps.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/sawyer_bin_picking/disc/02_eps_2-0x_sto_50000steps.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
        </tr>
        <tr>
            <td style="width: 10px; min-width: 8px; max-width: 40px">
                <!-- <div style=" transform: rotate(-90deg); white-space: nowrap"> -->
                <div style=" transform: rotate(-90deg); width: 100px; height: 100px">
                    100k steps
                </div>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/sawyer_bin_picking/multi-sqil/02_eps_2-0x_sto_100000steps.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/sawyer_bin_picking/sqil-no-vp/02_eps_2-0x_sto_100000steps.mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/sawyer_bin_picking/rce/02_eps_2-0x_sto_100000steps.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/sawyer_bin_picking/disc/02_eps_2-0x_sto_100000steps.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
        </tr>
        <tr>
            <td style="width: 10px; min-width: 8px; max-width: 40px">
                <!-- <div style=" transform: rotate(-90deg); white-space: nowrap"> -->
                <div style=" transform: rotate(-90deg); width: 100px; height: 100px">
                    150k steps
                </div>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/sawyer_bin_picking/multi-sqil/02_eps_2-0x_sto_150000steps.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/sawyer_bin_picking/sqil-no-vp/02_eps_2-0x_sto_150000steps.mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/sawyer_bin_picking/rce/02_eps_2-0x_sto_150000steps.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/sawyer_bin_picking/disc/02_eps_2-0x_sto_150000steps.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
        </tr>
    </table>
</div>
{:/}

#### hammer-human-v0-dp
{::nomarkdown}
<div style='text-align:center'>
    <table>
        <tr>
            <!-- <td style="width: 12px; min-width:10px"></td> -->
            <td style="width: 10px; min-width:8px"></td>
            <td> <font size="+1"> <b>VPACE</b> </font> </td>
            <td> SQIL </td>
            <td> RCE </td>
            <td> DAC </td>
        </tr>
        <tr>
            <td style="width: 10px; min-width: 8px; max-width: 40px">
                <!-- <div style=" transform: rotate(-90deg); white-space: nowrap"> -->
                <div style=" transform: rotate(-90deg); width: 100px; height: 100px">
                    200k steps
                </div>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/hammer-human-v0-dp/multi-sqil/02_eps_2-0x_sto_200000steps.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/hammer-human-v0-dp/sqil-no-vp/02_eps_2-0x_sto_200000steps.mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/hammer-human-v0-dp/rce/02_eps_2-0x_sto_200000steps.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/hammer-human-v0-dp/disc/02_eps_2-0x_sto_200000steps.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
        </tr>
        <tr>
            <td style="width: 10px; min-width: 8px; max-width: 40px">
                <!-- <div style=" transform: rotate(-90deg); white-space: nowrap"> -->
                <div style=" transform: rotate(-90deg); width: 100px; height: 100px">
                    400k steps
                </div>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/hammer-human-v0-dp/multi-sqil/02_eps_2-0x_sto_400000steps.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/hammer-human-v0-dp/sqil-no-vp/02_eps_2-0x_sto_400000steps.mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/hammer-human-v0-dp/rce/02_eps_2-0x_sto_400000steps.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/hammer-human-v0-dp/disc/02_eps_2-0x_sto_400000steps.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
        </tr>
        <tr>
            <td style="width: 10px; min-width: 8px; max-width: 40px">
                <!-- <div style=" transform: rotate(-90deg); white-space: nowrap"> -->
                <div style=" transform: rotate(-90deg); width: 100px; height: 100px">
                    600k steps
                </div>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/hammer-human-v0-dp/multi-sqil/02_eps_2-0x_sto_600000steps.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/hammer-human-v0-dp/sqil-no-vp/02_eps_2-0x_sto_600000steps.mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/hammer-human-v0-dp/rce/02_eps_2-0x_sto_600000steps.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/hammer-human-v0-dp/disc/02_eps_2-0x_sto_600000steps.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
        </tr>
    </table>
</div>
{:/}

#### relocate-human-v0-najp-dp
{::nomarkdown}
<div style='text-align:center'>
    <table>
        <tr>
            <!-- <td style="width: 12px; min-width:10px"></td> -->
            <td style="width: 10px; min-width:8px"></td>
            <td> <font size="+1"> <b>VPACE</b> </font> </td>
            <td> SQIL </td>
            <td> RCE </td>
            <td> DAC </td>
        </tr>
        <tr>
            <td style="width: 10px; min-width: 8px; max-width: 40px">
                <!-- <div style=" transform: rotate(-90deg); white-space: nowrap"> -->
                <div style=" transform: rotate(-90deg); width: 100px; height: 100px">
                    300k steps
                </div>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/relocate-human-v0-najp-dp/multi-sqil/02_eps_2-0x_sto_300000steps.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/relocate-human-v0-najp-dp/sqil-no-vp/02_eps_2-0x_sto_300000steps.mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/relocate-human-v0-najp-dp/rce/02_eps_2-0x_sto_300000steps.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/relocate-human-v0-najp-dp/disc/02_eps_2-0x_sto_300000steps.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
        </tr>
        <tr>
            <td style="width: 10px; min-width: 8px; max-width: 40px">
                <!-- <div style=" transform: rotate(-90deg); white-space: nowrap"> -->
                <div style=" transform: rotate(-90deg); width: 100px; height: 100px">
                    600k steps
                </div>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/relocate-human-v0-najp-dp/multi-sqil/02_eps_2-0x_sto_600000steps.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/relocate-human-v0-najp-dp/sqil-no-vp/02_eps_2-0x_sto_600000steps.mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/relocate-human-v0-najp-dp/rce/02_eps_2-0x_sto_600000steps.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/relocate-human-v0-najp-dp/disc/02_eps_2-0x_sto_600000steps.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
        </tr>
        <tr>
            <td style="width: 10px; min-width: 8px; max-width: 40px">
                <!-- <div style=" transform: rotate(-90deg); white-space: nowrap"> -->
                <div style=" transform: rotate(-90deg); width: 100px; height: 100px">
                    900k steps
                </div>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/relocate-human-v0-najp-dp/multi-sqil/02_eps_2-0x_sto_900000steps.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/relocate-human-v0-najp-dp/sqil-no-vp/02_eps_2-0x_sto_900000steps.mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/relocate-human-v0-najp-dp/rce/02_eps_2-0x_sto_900000steps.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/relocate-human-v0-najp-dp/disc/02_eps_2-0x_sto_600000steps.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
        </tr>
    </table>
</div>
{:/}

### Success Examples for Training
The numerical state data corresponding to these example success images was the only signal (i.e., no reward function and no full trajectories) used for training policies in this work.
We also show examples from the initial state distributions.

#### Panda Tasks
{::nomarkdown}
<div style='text-align:center'>
    <table>
        <tr>
            <td> Initial State (Shared) </td>
            <td> Initial State (Unstack-Stack) </td>
            <td> Release </td>
            <td> Grasp </td>
        </tr>
        <tr>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/reset_success_examples/bring_no_move_0_05_eps_reset.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/reset_success_examples/unstack_stack_env_only_no_move_0_05_eps_reset.mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/reset_success_examples/open_reach_05_eps_success.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/reset_success_examples/grasp_05_eps_success.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
        </tr>
        <tr>
            <td> Reach </td>
            <td> Lift </td>
            <td> Move </td>
            <td> Stack/Unstack-Stack </td>
        </tr>
        <tr>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/reset_success_examples/reach_0_05_eps_success.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/reset_success_examples/lift_0_05_eps_success.mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/reset_success_examples/move_obj_0_05_eps_success.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/reset_success_examples/stack_no_move_0_05_eps_success.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
        </tr>
        <tr>
            <td> Bring </td>
            <td> Insert </td>
            <td>  </td>
            <td>  </td>
        </tr>
        <tr>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/reset_success_examples/bring_no_move_0_05_eps_success.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/reset_success_examples/insert_no_bring_no_move_0_05_eps_success.mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
            </td>
            <td>
            </td>
        </tr>
    </table>
</div>
{:/}

#### Sawyer Tasks
{::nomarkdown}
<div style='text-align:center'>
    <table>
        <tr>
            <!-- <td style="width: 12px; min-width:10px"></td> -->
            <td style="width: 10px; min-width:8px"></td>
            <td> Initial State </td>
            <td> Reach </td>
            <td> Grasp </td>
            <td> Main </td>
        </tr>
        <tr>
            <td style="width: 10px; min-width: 8px; max-width: 40px">
                <!-- <div style=" transform: rotate(-90deg); white-space: nowrap"> -->
                <div style=" transform: rotate(-90deg); width: 100px; height: 100px">
                    Drawer Open
                </div>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/reset_success_examples/sawyer_drawer_open_05_eps_reset.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/reset_success_examples/sawyer_drawer_open_05_eps_reach.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/reset_success_examples/sawyer_drawer_open_05_eps_grasp.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/reset_success_examples/sawyer_drawer_open_05_eps_success.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
        </tr>
        <tr>
            <td style="width: 10px; min-width: 8px; max-width: 40px">
                <!-- <div style=" transform: rotate(-90deg); white-space: nowrap"> -->
                <div style=" transform: rotate(-90deg); width: 100px; height: 100px">
                    Drawer Close
                </div>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/reset_success_examples/sawyer_drawer_close_05_eps_reset.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/reset_success_examples/sawyer_drawer_close_05_eps_reach.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/reset_success_examples/sawyer_drawer_close_05_eps_grasp.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/reset_success_examples/sawyer_drawer_close_05_eps_success.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
        </tr>
        <tr>
            <td style="width: 10px; min-width: 8px; max-width: 40px">
                <!-- <div style=" transform: rotate(-90deg); white-space: nowrap"> -->
                <div style=" transform: rotate(-90deg); width: 100px; height: 100px">
                    Push
                </div>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/reset_success_examples/sawyer_push_05_eps_reset.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/reset_success_examples/sawyer_push_05_eps_reach.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/reset_success_examples/sawyer_push_05_eps_grasp.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/reset_success_examples/sawyer_push_05_eps_success.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
        </tr>
        <tr>
            <td style="width: 10px; min-width: 8px; max-width: 40px">
                <!-- <div style=" transform: rotate(-90deg); white-space: nowrap"> -->
                <div style=" transform: rotate(-90deg); width: 100px; height: 100px">
                    Lift
                </div>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/reset_success_examples/sawyer_lift_05_eps_reset.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/reset_success_examples/sawyer_lift_05_eps_reach.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/reset_success_examples/sawyer_lift_05_eps_grasp.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/reset_success_examples/sawyer_lift_05_eps_success.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
        </tr>
        <tr>
            <td style="width: 10px; min-width: 8px; max-width: 40px">
                <!-- <div style=" transform: rotate(-90deg); white-space: nowrap"> -->
                <div style=" transform: rotate(-90deg); width: 100px; height: 100px">
                    Box Close
                </div>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/reset_success_examples/sawyer_box_close_05_eps_reset.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/reset_success_examples/sawyer_box_close_05_eps_reach.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/reset_success_examples/sawyer_box_close_05_eps_grasp.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/reset_success_examples/sawyer_box_close_05_eps_success.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
        </tr>
        <tr>
            <td style="width: 10px; min-width: 8px; max-width: 40px">
                <!-- <div style=" transform: rotate(-90deg); white-space: nowrap"> -->
                <div style=" transform: rotate(-90deg); width: 100px; height: 100px">
                    Bin Picking
                </div>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/reset_success_examples/sawyer_bin_picking_05_eps_reset.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/reset_success_examples/sawyer_bin_picking_05_eps_reach.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/reset_success_examples/sawyer_bin_picking_05_eps_grasp.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/reset_success_examples/sawyer_bin_picking_05_eps_success.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
        </tr>
    </table>
</div>
{:/}

#### Adroit Hand Tasks
The same data was used for the original and the delta-position variants.

{::nomarkdown}
<div style='text-align:center'>
    <table>
        <tr>
            <!-- <td style="width: 12px; min-width:10px"></td> -->
            <td style="width: 10px; min-width:8px"></td>
            <td> Initial State </td>
            <td> Reach </td>
            <td> Grasp </td>
            <td> Main </td>
        </tr>
        <tr>
            <td style="width: 10px; min-width: 8px; max-width: 40px">
                <!-- <div style=" transform: rotate(-90deg); white-space: nowrap"> -->
                <div style=" transform: rotate(-90deg); width: 100px; height: 100px">
                    Door
                </div>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/reset_success_examples/door-human-v0_05_eps_reset.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/reset_success_examples/door-human-v0_05_eps_reach.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/reset_success_examples/door-human-v0_05_eps_grasp.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/reset_success_examples/door-human-v0_05_eps_success.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
        </tr>
        <tr>
            <td style="width: 10px; min-width: 8px; max-width: 40px">
                <!-- <div style=" transform: rotate(-90deg); white-space: nowrap"> -->
                <div style=" transform: rotate(-90deg); width: 100px; height: 100px">
                    Hammer
                </div>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/reset_success_examples/hammer-human-v0_05_eps_reset.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/reset_success_examples/hammer-human-v0_05_eps_reach.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/reset_success_examples/hammer-human-v0_05_eps_grasp.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/reset_success_examples/hammer-human-v0_05_eps_success.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
        </tr>
        <tr>
            <td style="width: 10px; min-width: 8px; max-width: 40px">
                <!-- <div style=" transform: rotate(-90deg); white-space: nowrap"> -->
                <div style=" transform: rotate(-90deg); width: 100px; height: 100px">
                    Relocate
                </div>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/reset_success_examples/relocate-human-v0_05_eps_reset.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/reset_success_examples/relocate-human-v0_05_eps_reach.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/reset_success_examples/relocate-human-v0_05_eps_grasp.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/reset_success_examples/relocate-human-v0_05_eps_success.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
        </tr>
    </table>
</div>
{:/}

### Final Performance (All Tasks)

#### Panda Hard Tasks
{::nomarkdown}
<div style='text-align:center'>
    <table>
        <tr>
            <!-- <td style="width: 12px; min-width:10px"></td> -->
            <td style="width: 10px; min-width:8px"></td>
            <td> <font size="+1"> <b>VPACE</b> </font> </td>
            <td> SQIL </td>
            <td> RCE </td>
            <td> DAC </td>
        </tr>
        <tr>
            <td style="width: 10px; min-width: 8px; max-width: 40px">
            	<!-- <div style=" transform: rotate(-90deg); white-space: nowrap"> -->
            	<div style=" transform: rotate(-90deg); width: 100px; height: 100px">
            		Stack
            	</div>
        	</td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/stack_no_move_0/multi-sqil/05_eps_3-0x.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/stack_no_move_0/sqil-no-vp/05_eps_3-0x.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/stack_no_move_0/rce/05_eps_3-0x.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/stack_no_move_0/disc/05_eps_3-0x.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
        </tr>
        <tr>
            <td style="width: 10px; min-width: 8px; max-width: 40px">
            	<!-- <div style=" transform: rotate(-90deg); white-space: nowrap"> -->
            	<div style=" transform: rotate(-90deg); width: 100px; height: 100px">
            		Unstack-Stack
            	</div>
        	</td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/unstack_stack_env_only_no_move_0/multi-sqil/05_eps_3-0x.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/unstack_stack_env_only_no_move_0/sqil-no-vp/05_eps_3-0x.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/unstack_stack_env_only_no_move_0/rce/05_eps_3-0x.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/unstack_stack_env_only_no_move_0/disc/05_eps_3-0x.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
        </tr>
        <tr>
            <td style="width: 10px; min-width: 8px; max-width: 40px">
            	<!-- <div style=" transform: rotate(-90deg); white-space: nowrap"> -->
            	<div style=" transform: rotate(-90deg); width: 100px; height: 100px">
            		Bring
            	</div>
        	</td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/bring_no_move_0/multi-sqil/05_eps_3-0x.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/bring_no_move_0/sqil-no-vp/05_eps_3-0x.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/bring_no_move_0/rce/05_eps_3-0x.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/bring_no_move_0/disc/05_eps_3-0x.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
        </tr>
        <tr>
            <td style="width: 10px; min-width: 8px; max-width: 40px">
            	<!-- <div style=" transform: rotate(-90deg); white-space: nowrap"> -->
            	<div style=" transform: rotate(-90deg); width: 100px; height: 100px">
            		Insert
            	</div>
        	</td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/insert_no_bring_no_move_0/multi-sqil/05_eps_3-0x.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/insert_no_bring_no_move_0/sqil-no-vp/05_eps_3-0x.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/insert_no_bring_no_move_0/rce/05_eps_3-0x.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/insert_no_bring_no_move_0/disc/05_eps_3-0x.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
        </tr>
    </table>
</div>
{:/}

#### Panda Easy Tasks
{::nomarkdown} 
<div style='text-align:center'>
    <table>
        <tr>
            <!-- <td style="width: 12px; min-width:10px"></td> -->
            <td style="width: 10px; min-width:8px"></td>
            <td> <font size="+1"> <b>VPACE</b> </font> </td>
            <td> SQIL </td>
            <td> RCE </td>
            <td> DAC </td>
        </tr>
        <tr>
            <td style="width: 10px; min-width: 8px; max-width: 40px">
            	<!-- <div style=" transform: rotate(-90deg); white-space: nowrap"> -->
            	<div style=" transform: rotate(-90deg); width: 100px; height: 100px">
            		Reach
            	</div>
        	</td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/reach_0/multi-sqil/05_eps_3-0x.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/reach_0/sqil-no-vp/05_eps_3-0x.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/reach_0/rce/05_eps_3-0x.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/reach_0/disc/05_eps_3-0x.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
        </tr>
        <tr>
            <td style="width: 10px; min-width: 8px; max-width: 40px">
            	<!-- <div style=" transform: rotate(-90deg); white-space: nowrap"> -->
            	<div style=" transform: rotate(-90deg); width: 100px; height: 100px">
            		Lift
            	</div>
        	</td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/lift_0/multi-sqil/05_eps_3-0x.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/lift_0/sqil-no-vp/05_eps_3-0x.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/lift_0/rce/05_eps_3-0x.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/lift_0/disc/05_eps_3-0x.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
        </tr>
        <tr>
            <td style="width: 10px; min-width: 8px; max-width: 40px">
            	<!-- <div style=" transform: rotate(-90deg); white-space: nowrap"> -->
            	<div style=" transform: rotate(-90deg); width: 100px; height: 100px">
            		Move
            	</div>
        	</td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/move_obj_0/multi-sqil/05_eps_3-0x.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/move_obj_0/sqil-no-vp/05_eps_3-0x.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/move_obj_0/rce/05_eps_3-0x.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/move_obj_0/disc/05_eps_3-0x.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
        </tr>
    </table>
</div>
{:/}

#### Sawyer Tasks
{::nomarkdown} 
<div style='text-align:center'>
    <table>
        <tr>
            <!-- <td style="width: 12px; min-width:10px"></td> -->
            <td style="width: 10px; min-width:8px"></td>
            <td> <font size="+1"> <b>VPACE</b> </font> </td>
            <td> SQIL </td>
            <td> RCE </td>
            <td> DAC </td>
        </tr>
        <tr>
            <td style="width: 10px; min-width: 8px; max-width: 40px">
            	<!-- <div style=" transform: rotate(-90deg); white-space: nowrap"> -->
            	<div style=" transform: rotate(-90deg); width: 100px; height: 100px">
            		Drawer Open
            	</div>
        	</td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/sawyer_drawer_open/multi-sqil/05_eps_3-0x.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/sawyer_drawer_open/sqil-no-vp/05_eps_3-0x.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/sawyer_drawer_open/rce/05_eps_3-0x.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/sawyer_drawer_open/disc/05_eps_3-0x.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
        </tr>
        <tr>
            <td style="width: 10px; min-width: 8px; max-width: 40px">
            	<!-- <div style=" transform: rotate(-90deg); white-space: nowrap"> -->
            	<div style=" transform: rotate(-90deg); width: 100px; height: 100px">
            		Drawer Close
            	</div>
        	</td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/sawyer_drawer_close/multi-sqil/05_eps_3-0x.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/sawyer_drawer_close/sqil-no-vp/05_eps_3-0x.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/sawyer_drawer_close/rce/05_eps_3-0x.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/sawyer_drawer_close/disc/05_eps_3-0x.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
        </tr>
        <tr>
            <td style="width: 10px; min-width: 8px; max-width: 40px">
            	<!-- <div style=" transform: rotate(-90deg); white-space: nowrap"> -->
            	<div style=" transform: rotate(-90deg); width: 100px; height: 100px">
            		Push
            	</div>
        	</td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/sawyer_push/multi-sqil/05_eps_3-0x.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/sawyer_push/sqil-no-vp/05_eps_3-0x.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/sawyer_push/rce/05_eps_3-0x.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/sawyer_push/disc/05_eps_3-0x.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
        </tr>
        <tr>
            <td style="width: 10px; min-width: 8px; max-width: 40px">
            	<!-- <div style=" transform: rotate(-90deg); white-space: nowrap"> -->
            	<div style=" transform: rotate(-90deg); width: 100px; height: 100px">
            		Lift
            	</div>
        	</td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/sawyer_lift/multi-sqil/05_eps_3-0x.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/sawyer_lift/sqil-no-vp/05_eps_3-0x.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/sawyer_lift/rce/05_eps_3-0x.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/sawyer_lift/disc/05_eps_3-0x.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
        </tr>
        <tr>
            <td style="width: 10px; min-width: 8px; max-width: 40px">
            	<!-- <div style=" transform: rotate(-90deg); white-space: nowrap"> -->
            	<div style=" transform: rotate(-90deg); width: 100px; height: 100px">
            		Box Close
            	</div>
        	</td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/sawyer_box_close/multi-sqil/05_eps_3-0x.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/sawyer_box_close/sqil-no-vp/05_eps_3-0x.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/sawyer_box_close/rce/05_eps_3-0x.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/sawyer_box_close/disc/05_eps_3-0x.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
        </tr>
        <tr>
            <td style="width: 10px; min-width: 8px; max-width: 40px">
            	<!-- <div style=" transform: rotate(-90deg); white-space: nowrap"> -->
            	<div style=" transform: rotate(-90deg); width: 100px; height: 100px">
            		Bin Picking
            	</div>
        	</td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/sawyer_bin_picking/multi-sqil/05_eps_3-0x.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/sawyer_bin_picking/sqil-no-vp/05_eps_3-0x.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/sawyer_bin_picking/rce/05_eps_3-0x.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/sawyer_bin_picking/disc/05_eps_3-0x.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
        </tr>
    </table>
</div>
{:/}

#### Adroit Delta-Position Hand Tasks
{::nomarkdown} 
<div style='text-align:center'>
    <table>
        <tr>
            <!-- <td style="width: 12px; min-width:10px"></td> -->
            <td style="width: 10px; min-width:8px"></td>
            <td> <font size="+1"> <b>VPACE</b> </font> </td>
            <td> SQIL </td>
            <td> RCE </td>
            <td> DAC </td>
        </tr>
        <tr>
            <td style="width: 10px; min-width: 8px; max-width: 40px">
            	<!-- <div style=" transform: rotate(-90deg); white-space: nowrap"> -->
            	<div style=" transform: rotate(-90deg); width: 100px; height: 100px">
            		Door (DP)
            	</div>
        	</td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/door-human-v0-dp/multi-sqil/05_eps_3-0x.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/door-human-v0-dp/sqil-no-vp/05_eps_3-0x.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/door-human-v0-dp/rce/05_eps_3-0x.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/door-human-v0-dp/disc/05_eps_3-0x.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
        </tr>
        <tr>
            <td style="width: 10px; min-width: 8px; max-width: 40px">
            	<!-- <div style=" transform: rotate(-90deg); white-space: nowrap"> -->
            	<div style=" transform: rotate(-90deg); width: 100px; height: 100px">
            		Hammer (DP)
            	</div>
        	</td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/hammer-human-v0-dp/multi-sqil/05_eps_3-0x.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/hammer-human-v0-dp/sqil-no-vp/05_eps_3-0x.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/hammer-human-v0-dp/rce/05_eps_3-0x.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/hammer-human-v0-dp/disc/05_eps_3-0x.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
        </tr>
        <tr>
            <td style="width: 10px; min-width: 8px; max-width: 40px">
            	<!-- <div style=" transform: rotate(-90deg); white-space: nowrap"> -->
            	<div style=" transform: rotate(-90deg); width: 100px; height: 100px">
            		Relocate (DP)
            	</div>
        	</td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/relocate-human-v0-najp-dp/multi-sqil/05_eps_3-0x.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/relocate-human-v0-najp-dp/sqil-no-vp/05_eps_3-0x.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/relocate-human-v0-najp-dp/rce/05_eps_3-0x.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/relocate-human-v0-najp-dp/disc/05_eps_3-0x.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
        </tr>
    </table>
</div>
{:/}

#### Adroit Absolute-Position Hand Tasks (Original)
{::nomarkdown} 
<div style='text-align:center'>
    <table>
        <tr>
            <!-- <td style="width: 12px; min-width:10px"></td> -->
            <td style="width: 10px; min-width:8px"></td>
            <td> <font size="+1"> <b>VPACE</b> </font> </td>
            <td> SQIL </td>
            <td> RCE </td>
            <td> DAC </td>
        </tr>
        <tr>
            <td style="width: 10px; min-width: 8px; max-width: 40px">
            	<!-- <div style=" transform: rotate(-90deg); white-space: nowrap"> -->
            	<div style=" transform: rotate(-90deg); width: 100px; height: 100px">
            		Door
            	</div>
        	</td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/door-human-v0/multi-sqil/05_eps_3-0x.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/door-human-v0/sqil-no-vp/05_eps_3-0x.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/door-human-v0/rce/05_eps_3-0x.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/door-human-v0/disc/05_eps_3-0x.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
        </tr>
        <tr>
            <td style="width: 10px; min-width: 8px; max-width: 40px">
            	<!-- <div style=" transform: rotate(-90deg); white-space: nowrap"> -->
            	<div style=" transform: rotate(-90deg); width: 100px; height: 100px">
            		Hammer
            	</div>
        	</td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/hammer-human-v0/multi-sqil/05_eps_3-0x.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/hammer-human-v0/sqil-no-vp/05_eps_3-0x.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/hammer-human-v0/rce/05_eps_3-0x.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/hammer-human-v0/disc/05_eps_3-0x.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
        </tr>
        <tr>
            <td style="width: 10px; min-width: 8px; max-width: 40px">
            	<!-- <div style=" transform: rotate(-90deg); white-space: nowrap"> -->
            	<div style=" transform: rotate(-90deg); width: 100px; height: 100px">
            		Relocate
            	</div>
        	</td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/relocate-human-v0/multi-sqil/05_eps_3-0x.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/relocate-human-v0/sqil-no-vp/05_eps_3-0x.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/relocate-human-v0/rce/05_eps_3-0x.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video width='100%' autoplay loop muted>
                    <source src='/assets/vpace/vids/relocate-human-v0/disc/05_eps_3-0x.mp4' type='video/mp4'>
                    Your browser does not support the video tag.
                </video>
            </td>
        </tr>
    </table>
</div>
{:/}