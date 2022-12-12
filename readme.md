# Vol-NeRF: An Unbounded Representation for Medical Volume Data
## CVPR 2023 Submission #3358 

![Overall architecture](imgs/overall.png)

## Arbitrary Views
* axis $\overset{\rightarrow}{n}=(1, 0, 0)$
* axis $\overset{\rightarrow}{n}=(0, 1, 0)$

* axis $\overset{\rightarrow}{n}=(\frac{\sqrt{2}}{2}, \frac{\sqrt{2}}{2}, 0)$
* axis $\overset{\rightarrow}{n}=(\frac{\sqrt{2}}{2}, 0, \frac{\sqrt{2}}{2})$
* axis $\overset{\rightarrow}{n}=(0, \frac{\sqrt{2}}{2}, \frac{\sqrt{2}}{2})$

<table rules="none" align="center">
	<tr>
		<td>
			<center>
				<img src="imgs/nerf/KiTS19_00105_aixs=011.gif" width="100%" />
				<br/>
				<font color="AAAAAA">NeRF</font>
			</center>
		</td>
		<td>
			<center>
				<img src="imgs/volnerf/KiTS19_00105_aixs=011.gif" width="100%" />
				<br/>
				<font color="AAAAAA"><em>Vol-NeRF</em> (Ours)</font>
			</center>
		</td>
	</tr>
</table>

* axis $\overset{\rightarrow}{n}=(\frac{\sqrt{3}}{3}, \frac{\sqrt{3}}{3}, \frac{\sqrt{3}}{3})$



## Arbitrary scales
<table rules="none" align="center">
	<tr>
		<td>
			<center>
				<img src="imgs/nerf/KiTS19_00000_multi_scale.gif" width="100%" />
				<br/>
				<font color="AAAAAA">NeRF</font>
			</center>
		</td>
		<td>
			<center>
				<img src="imgs/volnerf/KiTS19_00000_multi_scale.gif" width="100%" />
				<br/>
				<font color="AAAAAA"><em>Vol-NeRF</em> (Ours)</font>
			</center>
		</td>
	</tr>
</table>
