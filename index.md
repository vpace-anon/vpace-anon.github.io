---
layout: minimal
title: VPACE for Learning without Rewards or Demonstrations (CoRL 2024)
subtitle: Value-Penalized Auxiliary Control from Examples for Learning without Rewards or Demonstrations
description: CoRL Submission on Learning from examples (i.e. no rewards or full-trajectory demonstrations) using value-penalization and auxiliary control.
nav_exclude: true
usemathjax: true
---

# Value-Penalized Auxiliary Control from Examples **(VPACE)** for Learning without Rewards or Demonstrations
{: .no_toc }


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

## Final Performance

### Panda Hard Tasks
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

### Panda Easy Tasks
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

### Sawyer Tasks
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

### Adroit Delta-Position Hand Tasks
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

### Adroit Absolute-Position Hand Tasks (Original)
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