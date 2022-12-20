# Vol-NeRF: An Unbounded Representation for Medical Volume Data
## CVPR 2023 Submission #3358 

![Overall architecture](imgs/overall.png)

## Arbitrary Views
* axis $\overset{\rightarrow}{n}=(1, 0, 0)$

<table rules="none" align="center">
	<tr>
		<td>
			<center>
  				<img src="imgs/nerf/KiTS19_00105_multi_section_test_axis=100.gif" width=100%>
				<br/>
				<font color="AAAAAA">NeRF</font>
			</center>
		</td>
		<td>
			<center>
				<img src="imgs/volnerf/KiTS19_00105_multi_section_test_axis=100.gif" width=100%>
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
  				<img src="imgs/nerf/MSD_colon_175_multi_section_test_axis=010.gif" width=100%>
				<br/>
				<font color="AAAAAA">NeRF</font>
			</center>
		</td>
		<td>
			<center>
				<img src="imgs/volnerf/MSD_colon_175_multi_section_test_axis=010.gif" width=100%>
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
  				<img src="imgs/nerf/MSD_liver_167_multi_section_test_axis=110.gif" width=100%>
				<br/>
				<font color="AAAAAA">NeRF</font>
			</center>
		</td>
		<td>
			<center>
				<img src="imgs/volnerf/MSD_liver_167_multi_section_test_axis=110.gif" width=100%>
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
  				<img src="imgs/nerf/MSD_colon_065_multi_section_test_axis=101.gif" width=100%>
				<br/>
				<font color="AAAAAA">NeRF</font>
			</center>
		</td>
		<td>
			<center>
				<img src="imgs/volnerf/MSD_colon_065_multi_section_test_axis=101.gif" width=100%>
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
  				<img src="imgs/nerf/KiTS19_00000_multi_section_test_axis=011.gif" width=100%>
				<br/>
				<font color="AAAAAA">NeRF</font>
			</center>
		</td>
		<td>
			<center>
				<img src="imgs/volnerf/KiTS19_00000_multi_section_test_axis=011.gif" width=100%>
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
  				<img src="imgs/nerf/MSD_colon_046_multi_section_test_axis=111.gif" width=100%>
				<br/>
				<font color="AAAAAA">NeRF</font>
			</center>
		</td>
		<td>
			<center>
				<img src="imgs/volnerf/MSD_colon_046_multi_section_test_axis=111.gif" width=100%>
				<br/>
				<font color="AAAAAA"><em>Vol-NeRF</em> (Ours)</font>
			</center>
		</td>
	</tr>
</table>

## Arbitrary scales

<table rules="none" align="center">
	<tr>
		<td>
			<center>
  				<img src="imgs/nerf/ADNI_130_S_5059_MR_Field_Mapping__br_raw_20130510152851115_107_S189115_I371965_multi_scale_test.gif" width=100%>
				<br/>
				<font color="AAAAAA">NeRF</font>
			</center>
		</td>
		<td>
			<center>
				<img src="imgs/volnerf/ADNI_130_S_5059_MR_Field_Mapping__br_raw_20130510152851115_107_S189115_I371965_multi_scale_test.gif" width=100%>
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
  				<img src="imgs/nerf/KiTS19_00000_multi_scale_test.gif" width=100%>
				<br/>
				<font color="AAAAAA">NeRF</font>
			</center>
		</td>
		<td>
			<center>
				<img src="imgs/volnerf/KiTS19_00000_multi_scale_test.gif" width=100%>
				<br/>
				<font color="AAAAAA"><em>Vol-NeRF</em> (Ours)</font>
			</center>
		</td>
	</tr>
</table>
