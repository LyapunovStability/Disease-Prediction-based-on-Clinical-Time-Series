
# Disease Prediction based on Clinical Time Series Data
## DATA
**Property**
* Irregularity
	* Non-uniform sampled-----x axis
	* The time interval is varying between time points 
	* The sampling density changes over different time periods

* Multple Variates 
	* HR(heartrate),Glucose...-----y axis

<p align="center">
    <img src="output.png" width="500" align="center">
</p>

**Figure.1** The illustration of one clinical time series sample (collected from the first 48 hours into ICU)



## Related Works


<table border=0 cellpadding=0 cellspacing=0 >
    <col width="5%" style='mso-width-source:userset;mso-width-alt:6848'>
	<col width="65%" style='mso-width-source:userset;mso-width-alt:26080'>
	<col width="25%" style='mso-width-source:userset;mso-width-alt:4032'>
	<col width="5%" style='mso-width-source:userset;mso-width-alt:4032'>
	<tr height=19 style='height:14.25pt'>
		<td class=xl6519452 width="5%" align="center">Year</td>
		<td class=xl6519452 width="15%" align="center">Conference</td>
		<td class=xl6519452 width="70%" align="center">Title</td>
		<td class=xl6519452 width="5%" align="center">Model Type</td>
		<td class=xl6519452 width="5%" align="center">Materials</td>
	</tr>
	<tr height=19 style='height:14.15pt'>
		<td class=xl6519452 align="center">2020</td>
		<td class=xl6519452 align="center">AAAI</td>
        <td class=xl6519452 align="center"><a href="https://arxiv.org/pdf/2206.10189.pdf">Data-gru: Dual-attention time-aware gated recurrent unit for irregular multivariate time series</a></td>
		<td class=xl6519452 align="center">RNN</td>
		<td class=xl6519452 align="center"></td>
	</tr>
	<tr height=19 style='height:14.15pt'>
		<td class=xl6519452 align="center">2021</td>
		<td class=xl6519452 align="center">IJCAI</td>
        <td class=xl6519452 align="center"><a href="https://arxiv.org/pdf/2206.10189.pdf">Cooperative Joint Attentive Network for Patient Outcome Prediction on Irregular Multi-Rate Multivariate Health Data</a></td>
		<td class=xl6519452 align="center">RNN</td>
		<td class=xl6519452 align="center"></td>
	</tr>
	<tr height=19 style='height:14.15pt'>
		<td class=xl6519452 align="center">2021</td>
		<td class=xl6519452 align="center">ICLR</td>
        <td class=xl6519452 align="center"><a href="https://arxiv.org/abs/2101.10318">Multi-Time Attention Networks for Irregularly Sampled Time Series</a></td>
		<td class=xl6519452 align="center">Transformer</td>
		<td class=xl6519452 align="center"></td>
	</tr>
	<tr height=19 style='height:14.15pt'>
		<td class=xl6519452 align="center">2023</td>
		<td class=xl6519452 align="center">KDD</td>
        <td class=xl6519452 align="center"><a href="https://arxiv.org/abs/2306.09368">Warpformer: A Multi-scale Modeling Approach for Irregular Clinical Time Series</a></td>
		<td class=xl6519452 align="center">Transformer</td>
		<td class=xl6519452 align="center"></td>
	</tr>
</table>



## Package
* Python ([学习网站](https://www.runoob.com/python3/python3-install.html))
	* 可以动手在自己的PC上配置环境，并且编写代码
* Pytorch ([学习材料](https://github.com/xiaotudui/pytorch-tutorial))
	* 目前暂时不需要动手，只是学习编程语言即可



## Learning Material: 
* Dive into Deep Learning 动手学深度学习 ([官网](https://d2l.ai/))
* Machine Learning Courses from Hung-yi Lee 通俗易懂的深度学习课程
	* Video([学习视频](https://www.bilibili.com/video/BV1NX4y1r7nP/?spm_id_from=333.337.search-card.all.click))
	* PDF ([官网](https://speech.ee.ntu.edu.tw/~hylee/ml/2023-spring.php))


## Paper Discussion: 

<table border=0 cellpadding=0 cellspacing=0 >
    <col width="40%" style='mso-width-source:userset;mso-width-alt:6848'>
	<col width="20%" style='mso-width-source:userset;mso-width-alt:26080'>
	<col width="25%" style='mso-width-source:userset;mso-width-alt:4032'>
	<tr height=19 style='height:14.25pt'>
		<td class=xl6519452 width="5%" align="center">Paper</td>
		<td class=xl6519452 width="15%" align="center">Discussion Time</td>
		<td class=xl6519452 width="70%" align="center">Keywords</td>
	</tr>
	<tr height=19 style='height:14.15pt'>
		<td class=xl6519452 align="center"><a href="https://arxiv.org/abs/2306.09368">Warpformer: A Multi-scale Modeling Approach for Irregular Clinical Time Series</a></td>
		<td class=xl6519452 align="center">2023.8.10</td>
		<td class=xl6519452 align="center">Dynamic Time  Warping</td>
	</tr>
</table>