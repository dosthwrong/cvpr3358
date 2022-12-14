# Vol-NeRF: An Unbounded Representation for Medical Volume Data
## CVPR 2023 Submission #3358 

![Overall architecture](imgs/overall.png)

## Arbitrary Views
* axis $\overset{\rightarrow}{n}=(1, 0, 0)$
* axis $\overset{\rightarrow}{n}=(0, 1, 0)$

<table rules="none" align="center">
	<tr>
		<td>
			<center>
				<video width="100%" controls>
  					<source src="imgs/nerf/kits_00000_axis010.mp4" type="video/mp4">
				</video>
				<br/>
				<font color="AAAAAA">NeRF</font>
			</center>
		</td>
		<td>
			<center>
				<video width="100%" controls>
  					<source src="imgs/volnerf/kits_00000_axis010.mp4" type="video/mp4">
				</video>
				<br/>
				<font color="AAAAAA"><em>Vol-NeRF</em> (Ours)</font>
			</center>
		</td>
	</tr>
</table>

* axis $\overset{\rightarrow}{n}=(\frac{\sqrt{2}}{2}, \frac{\sqrt{2}}{2}, 0)$

<!-- <table rules="none" align="center">
	<tr>
		<td>
			<center>
				<video src="imgs/nerf/kits_00105_aixs010.mp4"/>
				<br/>
				<font color="AAAAAA">NeRF</font>
			</center>
		</td>
		<td>
			<center>
				<video src="imgs/volnerf/kits_00105_aixs010.mp4"/>
				<br/>
				<font color="AAAAAA"><em>Vol-NeRF</em> (Ours)</font>
			</center>
		</td>
	</tr>
</table> -->

* axis $\overset{\rightarrow}{n}=(\frac{\sqrt{2}}{2}, 0, \frac{\sqrt{2}}{2})$
* axis $\overset{\rightarrow}{n}=(0, \frac{\sqrt{2}}{2}, \frac{\sqrt{2}}{2})$



* axis $\overset{\rightarrow}{n}=(\frac{\sqrt{3}}{3}, \frac{\sqrt{3}}{3}, \frac{\sqrt{3}}{3})$



## Arbitrary scales
<!-- <table rules="none" align="center">
	<tr>
		<td>
			<center>
				<video src="imgs/nerf/KiTS19_00000_multi_scale.gif"/>
				<br/>
				<font color="AAAAAA">NeRF</font>
			</center>
		</td>
		<td>
			<center>
				<video src="imgs/volnerf/KiTS19_00000_multi_scale.gif"/>
				<br/>
				<font color="AAAAAA"><em>Vol-NeRF</em> (Ours)</font>
			</center>
		</td>
	</tr>
</table> -->
