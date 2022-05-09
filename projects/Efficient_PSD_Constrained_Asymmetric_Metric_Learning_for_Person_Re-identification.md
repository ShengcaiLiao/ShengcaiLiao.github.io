## Efficient PSD Constrained Asymmetric Metric Learning for Person Re-identification

### Problems with existing metric learning methods

* Applying PSD: expensive
* No PSD: noisy
* pos/neg samples: largely unbalanced

### Contributions

* APG solution to the PSD constrained logistic metric learning problem
* Asymmetric pos/neg sample weights to balance pos/neg costs

### Advantages

* PSD+APG leads to low rank and smooth metric
* APG solution is fast in convergence
* PSD and asymmetric weights lead to notable improvements

### Download

* Download: [MLAPG.zip](https://sourceforge.net/projects/openpr/files/code%20for%20an%20individual%20algorithm/MLAPG.zip)
* CMC curves: [cmc_curves.zip](https://1drv.ms/u/s!AtFUxkZAZIU-eIQS6rK5mI2t1sw)

### Results

<div align=center>
    <table style="margin-left: auto; margin-right: auto;">
        <tr>
            <td>
                <div class="box">
                    <img src="../image/mlapg-rank.jpeg" width="300px"><br/>
                    Fig. 1. Fast rank shrinkage.
                </div>
            </td>
            <td>
                <div class="box">
                    <img src="../image/mlapg-dims.jpeg" width="300px"><br/>
                    Fig. 2. Effect of low rank selection.
                </div>
            </td>
        </tr>
        <tr>
            <td>
                <div class="box">
                    <img src="../image/mlapg-psd.jpeg" width="300px"><br/>
                    Fig. 3. Improvement by PSD.
                </div>
            </td>
            <td>
                <div class="box">
                    <img src="../image/mlapg-weight.jpeg" width="300px"><br/>
                    Fig. 4. Improvement by weighting.
                </div>
            </td>
        </tr>
    </table>

  Table 1. Summary of results (%) for the proposed MLAPG algorithm<br/>
    <img src="../image/psd_result.png" width="300px"><br/>

</div>
Note: CMC curves of the proposed MLAPG algorithm can be downloaded in [cmc_curves.zip](https://1drv.ms/u/s!AtFUxkZAZIU-eIQS6rK5mI2t1sw)

### Contact:
<img src="../image/email.webp" height="30px">
<p>National Laboratory of Pattern Recognition, Institute of Automation, Chinese Academy of Sciences.</p>

### References:

[1]Shengcai Liao and Stan Z. Li, “Efficient PSD Constrained Asymmetric Metric Learning for Person Re-identification.” In IEEE International Conference on Computer Vision (ICCV 2015), December 11-18, Santiago, Chile, 2015. [[pdf](../doc/liao-iccv15-mlapg-1.pdf)] [[poster](../doc/mlapg_iccv2015_poster-1.pdf)]

Last updated: Dec. 8, 2015

