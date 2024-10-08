# Shift-view Prompt Tuning: A Novel Training Pipeline for Visual Tracking
# Abstract
Most SOTA visual trackers are constant-view trackers, $i.e.$,they are designed for tracking scenarios collected from fixed-view cameras. However, when they are applied to shift-view tracking scenarios, their effectiveness is limited, primarily due to the significant differences between the two scenarios, particularly in terms of target scale variations and environmental complexity variations. This limitation stems from the conventional offline training approaches, which solely collect constant-view data to train existing visual trackers, making them difficult to adapt for shift-view tracking scenarios. 
Thus, we propose a novel training approach called Shift-view Prompt Tuning, which introduces shift-view prompts that adapt trackers to shift-view tracking scenarios in a cost-effective way. Our method consists of two components: the View Prompt Selector (VPS) and the Prompt Synthesizer (PS). The VPS generates powerful shift-view prompts from existing different view candidate datasets by leveraging invariant target semantic information across different view data. The PS synthesizes shift-view tokens using shift-view prompts, facilitating trackers’ adaptability for shift-view tracking scenarios. Extensive experiments on different tracking datasets demonstrate our proposed method’s effectiveness, efficiency, and strong generalization capabilities.
# Visual comparisons
<div align=center>
	<img src="./fig/fig.png"/>
</div>
