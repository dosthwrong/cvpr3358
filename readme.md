# Vol-NeRF: An Unbounded Representation for Medical Volume Data
## CVPR 2023 Submission #3358 

![Overall architecture](imgs/overall.png)

## Arbitrary Views
* axis $\overset{\rightarrow}{n}=(1, 0, 0)$

<table rules="none" align="center">
	<tr>
		<td>
			<center>
  				<img src="imgs/nerf/KiTS19_00105_axis100.gif" width=100%>
				<br/>
				<font color="AAAAAA">NeRF</font>
			</center>
		</td>
		<td>
			<center>
				<img src="imgs/volnerf/KiTS19_00105_axis100.gif" width=100%>
				<br/>
				<font color="AAAAAA"><em>Vol-NeRF</em> (Ours)</font>
			</center>
		</td>
	</tr>
</table>

* axis $\overset{\rightarrow}{n}=(0, 1, 0)$

<table rules="none" align="center">
	<tr>
		<td>
			<center>
  				<img src="imgs/nerf/KiTS19_00000_axis010.gif" width=100%>
				<br/>
				<font color="AAAAAA">NeRF</font>
			</center>
		</td>
		<td>
			<center>
				<img src="imgs/volnerf/KiTS19_00000_axis010.gif" width=100%>
				<br/>
				<font color="AAAAAA"><em>Vol-NeRF</em> (Ours)</font>
			</center>
		</td>
	</tr>
</table>

* axis $\overset{\rightarrow}{n}=(\frac{\sqrt{2}}{2}, \frac{\sqrt{2}}{2}, 0)$

<table rules="none" align="center">
	<tr>
		<td>
			<center>
  				<img src="imgs/nerf/KiTS19_00144_axis110.gif" width=100%>
				<br/>
				<font color="AAAAAA">NeRF</font>
			</center>
		</td>
		<td>
			<center>
				<img src="imgs/volnerf/KiTS19_00144_axis110.gif" width=100%>
				<br/>
				<font color="AAAAAA"><em>Vol-NeRF</em> (Ours)</font>
			</center>
		</td>
	</tr>
</table>

<table rules="none" align="center">
	<tr>
		<td>
			<center>
  				<img src="imgs/nerf/MSD_colon_046_axis110.gif" width=100%>
				<br/>
				<font color="AAAAAA">NeRF</font>
			</center>
		</td>
		<td>
			<center>
				<img src="imgs/volnerf/MSD_colon_046_axis110.gif" width=100%>
				<br/>
				<font color="AAAAAA"><em>Vol-NeRF</em> (Ours)</font>
			</center>
		</td>
	</tr>
</table>

<table rules="none" align="center">
	<tr>
		<td>
			<center>
  				<img src="imgs/nerf/MSD_liver_167_axis110.gif" width=100%>
				<br/>
				<font color="AAAAAA">NeRF</font>
			</center>
		</td>
		<td>
			<center>
				<img src="imgs/volnerf/MSD_liver_167_axis110.gif" width=100%>
				<br/>
				<font color="AAAAAA"><em>Vol-NeRF</em> (Ours)</font>
			</center>
		</td>
	</tr>
</table>

* axis $\overset{\rightarrow}{n}=(\frac{\sqrt{2}}{2}, 0, \frac{\sqrt{2}}{2})$

<table rules="none" align="center">
	<tr>
		<td>
			<center>
  				<img src="imgs/nerf/KiTS19_00144_axis101.gif" width=100%>
				<br/>
				<font color="AAAAAA">NeRF</font>
			</center>
		</td>
		<td>
			<center>
				<img src="imgs/volnerf/KiTS19_00144_axis101.gif" width=100%>
				<br/>
				<font color="AAAAAA"><em>Vol-NeRF</em> (Ours)</font>
			</center>
		</td>
	</tr>
</table>

* axis $\overset{\rightarrow}{n}=(0, \frac{\sqrt{2}}{2}, \frac{\sqrt{2}}{2})$

<table rules="none" align="center">
	<tr>
		<td>
			<center>
  				<img src="imgs/nerf/KiTS19_00000_axis011.gif" width=100%>
				<br/>
				<font color="AAAAAA">NeRF</font>
			</center>
		</td>
		<td>
			<center>
				<img src="imgs/volnerf/KiTS19_00000_axis011.gif" width=100%>
				<br/>
				<font color="AAAAAA"><em>Vol-NeRF</em> (Ours)</font>
			</center>
		</td>
	</tr>
</table>

<table rules="none" align="center">
	<tr>
		<td>
			<center>
  				<img src="imgs/nerf/KiTS19_00105_axis011.gif" width=100%>
				<br/>
				<font color="AAAAAA">NeRF</font>
			</center>
		</td>
		<td>
			<center>
				<img src="imgs/volnerf/KiTS19_00105_axis011.gif" width=100%>
				<br/>
				<font color="AAAAAA"><em>Vol-NeRF</em> (Ours)</font>
			</center>
		</td>
	</tr>
</table>

* axis $\overset{\rightarrow}{n}=(\frac{\sqrt{3}}{3}, \frac{\sqrt{3}}{3}, \frac{\sqrt{3}}{3})$

<table rules="none" align="center">
	<tr>
		<td>
			<center>
  				<img src="imgs/nerf/MSD_colon_046_axis111.gif" width=100%>
				<br/>
				<font color="AAAAAA">NeRF</font>
			</center>
		</td>
		<td>
			<center>
				<img src="imgs/volnerf/MSD_colon_046_axis111.gif" width=100%>
				<br/>
				<font color="AAAAAA"><em>Vol-NeRF</em> (Ours)</font>
			</center>
		</td>
	</tr>
</table>

<table rules="none" align="center">
	<tr>
		<td>
			<center>
  				<img src="imgs/nerf/MSD_liver_167_axis111.gif" width=100%>
				<br/>
				<font color="AAAAAA">NeRF</font>
			</center>
		</td>
		<td>
			<center>
				<img src="imgs/volnerf/MSD_liver_167_axis111.gif" width=100%>
				<br/>
				<font color="AAAAAA"><em>Vol-NeRF</em> (Ours)</font>
			</center>
		</td>
	</tr>
</table>

## Arbitrary scales

