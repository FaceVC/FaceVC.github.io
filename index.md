# FaceVC

This is the demo webpage for the expiriments in 'Face-based Voice Conversion: Learning the Voice behind a Face'.


## Outline

**1. FaceVC demo**

**2. Conversion Interpolation**

**3. Failure Case**


## FaceVC demo

<table border="0" cellpadding="0" cellspacing="0" style="width: 100%;">
<tbody>
    <tr>
        <td ALIGN=CENTER valign=CENTER>　<p>Speaker photo</p>　</td>
        <td ALIGN=CENTER valign=CENTER>　<p>FaceVC</p>　</td>
        <td ALIGN=CENTER valign=CENTER>　<p>Ground Truth</p>　</td>
    </tr>
    <tr>
        <td ALIGN=CENTER>　<img alt="" src="img/male/06M8qY7Q74Y_00015.jpg" width="150"/>　</td>
        <td ALIGN=CENTER VALIGN=CENTER>　<audio
            controls
            src="audio/Gwarp_fixG_MSE_tune1/p333_027.npyx06M8qY7Q74Y-00001.npy.wav">
                Your browser does not support the
                <code>audio</code> element.
        </audio>　</td>
        <td ALIGN=CENTER VALIGN=CENTER>　<audio
            controls
            src="audio/GT/06M8qY7Q74Y-00001.wav">
                Your browser does not support the
                <code>audio</code> element.
        </audio>　</td>
    </tr>
    <tr>
        <td ALIGN=CENTER>　<img alt="" src="img/B.jpg" width="150"/>　</td>
        <td ALIGN=CENTER VALIGN=CENTER>　<audio
            controls
            src="audio/A2B.wav">
                Your browser does not support the
                <code>audio</code> element.
        </audio>　</td>
        <td ALIGN=CENTER VALIGN=CENTER>　<audio
            controls
            src="audio/B2B.wav">
                Your browser does not support the
                <code>audio</code> element.
        </audio>　</td>
    </tr>
    <tr>
        <td ALIGN=CENTER>　<img alt="" src="img/C.jpg" width="150"/>　</td>
        <td ALIGN=CENTER VALIGN=CENTER>　<audio
            controls
            src="audio/A2C.wav">
                Your browser does not support the
                <code>audio</code> element.
        </audio>　</td>
        <td ALIGN=CENTER VALIGN=CENTER>　<audio
            controls
            src="audio/B2C.wav">
                Your browser does not support the
                <code>audio</code> element.
        </audio>　</td>
    </tr>
    <tr>
        <td ALIGN=CENTER>　<img alt="" src="img/D.jpg" width="150"/>　</td>
        <td ALIGN=CENTER VALIGN=CENTER>　<audio
            controls
            src="audio/A2D.wav">
                Your browser does not support the
                <code>audio</code> element.
        </audio>　</td>
        <td ALIGN=CENTER VALIGN=CENTER>　<audio
            controls
            src="audio/B2D.wav">
                Your browser does not support the
                <code>audio</code> element.
        </audio>　</td>
    </tr>
</tbody></table>


## Zero-Shot Conversion

<table border="0" cellpadding="0" cellspacing="0" style="width: 100%;">
<tbody><tr>
<td ALIGN=CENTER>　<p>Speaker photo</p>　</td>
<td ALIGN=CENTER>　<p>Synthesized Voice</p>　</td>
<td ALIGN=CENTER>　<p>Ground Truth Voice</p>　</td>
</tr>
<tr>
<td ALIGN=CENTER>　<img alt="" src="img/E.jpg"  width="150"/>　</td>
<td ALIGN=CENTER>　<audio
    controls
    src="audio/E_gen.wav">
        Your browser does not support the
        <code>audio</code> element.
</audio>　</td>
<td ALIGN=CENTER>　<audio
    controls
    src="audio/E_ori.wav">
        Your browser does not support the
        <code>audio</code> element.
</audio>　</td>
</tr>
<tr>
<td ALIGN=CENTER>　<img alt="" src="img/F.jpg"  width="150"/>　</td>
<td ALIGN=CENTER>　<audio
    controls
    src="audio/F_gen.wav">
        Your browser does not support the
        <code>audio</code> element.
</audio>　</td>
<td ALIGN=CENTER>　<audio
    controls
    src="audio/F_ori.wav">
        Your browser does not support the
        <code>audio</code> element.
</audio>　</td>
</tr>
<tr>
<td ALIGN=CENTER>　<img alt="" src="img/G.jpg"  width="150"/>　</td>
<td ALIGN=CENTER>　<audio
    controls
    src="audio/G_gen.wav">
        Your browser does not support the
        <code>audio</code> element.
</audio>　</td>
<td ALIGN=CENTER>　<audio
    controls
    src="audio/G_ori.wav">
        Your browser does not support the
        <code>audio</code> element.
</audio>　</td>
</tr>
<tr>
<td ALIGN=CENTER>　<img alt="" src="img/H.jpg"  width="150"/>　</td>
<td ALIGN=CENTER>　<audio
    controls
    src="audio/H_gen.wav">
        Your browser does not support the
        <code>audio</code> element.
</audio>　</td>
<td ALIGN=CENTER>　<audio
    controls
    src="audio/H_ori.wav">
        Your browser does not support the
        <code>audio</code> element.
</audio>　</td>
</tr></tbody></table>



## Failure Case
<table border="0" cellpadding="0" cellspacing="0" style="width: 100%;">
<tbody><tr>
<td ALIGN=CENTER>　<p>Speaker photo</p>　</td>
<td ALIGN=CENTER>　<p>Synthesized Voice</p>　</td>
<td ALIGN=CENTER>　<p>Ground Truth Voice</p>　</td>
</tr>
<tr>
<td ALIGN=CENTER>　<img alt="" src="img/J.jpg"  width="150"/>　</td>
<td ALIGN=CENTER>　<audio
    controls
    src="audio/J_gen.wav">
        Your browser does not support the
        <code>audio</code> element.
</audio>　</td>
<td ALIGN=CENTER>　<audio
    controls
    src="audio/J_ori.wav">
        Your browser does not support the
        <code>audio</code> element.
</audio>　</td>
</tr>
<tr>
<td ALIGN=CENTER>　<img alt="" src="img/K.jpg"  width="150"/>　</td>
<td ALIGN=CENTER>　<audio
    controls
    src="audio/K_gen.wav">
        Your browser does not support the
        <code>audio</code> element.
</audio>　</td>
<td ALIGN=CENTER>　<audio
    controls
    src="audio/K_ori.wav">
        Your browser does not support the
        <code>audio</code> element.
</audio>　</td>
</tr></tbody></table>




## Conversion Interpolation
<table border="0" cellpadding="0" cellspacing="0" style="width: 100%;">
<tbody><tr>
<td ALIGN=CENTER>　<p>A</p>　</td>
<td ALIGN=CENTER>　<p>B</p>　</td>
</tr>
<tr>
<td ALIGN=CENTER>　<img alt="" src="img/A.jpg"  width="150"/>　</td>
<td ALIGN=CENTER>　<img alt="" src="img/B.jpg"  width="150"/>　</td>
</tr></tbody></table>



<table border="0" cellpadding="0" cellspacing="0" style="width: 100%;">
<tbody><tr>
<td ALIGN=CENTER>　<p>Ratio</p>　</td>
<td ALIGN=CENTER>　<p>Before Reparameterization</p>　</td>
<td ALIGN=CENTER>　<p>After Reparameterization</p>　</td>
</tr>
<tr>
<td ALIGN=CENTER>　<p>0.0A + 1.0B</p>　</td>
<td ALIGN=CENTER>　<audio
    controls
    src="inter/attn_only/2ZviHInGBJQ-00031.npyx0nI65jgHG9o-00005.npy_0.wav">
        Your browser does not support the
        <code>audio</code> element.
</audio>　</td>
<td ALIGN=CENTER>　<audio
    controls
    src="inter/our/2ZviHInGBJQ-00031.npyx0nI65jgHG9o-00005.npy_0.wav">
        Your browser does not support the
        <code>audio</code> element.
</audio>　</td>
</tr>
<tr>
<td ALIGN=CENTER>　<p>0.1A + 0.9B</p>　</td>
<td ALIGN=CENTER>　<audio
    controls
    src="inter/attn_only/2ZviHInGBJQ-00031.npyx0nI65jgHG9o-00005.npy_0.1.wav">
        Your browser does not support the
        <code>audio</code> element.
</audio>　</td>
<td ALIGN=CENTER>　<audio
    controls
    src="inter/our/2ZviHInGBJQ-00031.npyx0nI65jgHG9o-00005.npy_0.1.wav">
        Your browser does not support the
        <code>audio</code> element.
</audio>　</td>
</tr>
<tr>
<td ALIGN=CENTER>　<p>0.2A + 0.8B</p>　</td>
<td ALIGN=CENTER>　<audio
    controls
    src="inter/attn_only/2ZviHInGBJQ-00031.npyx0nI65jgHG9o-00005.npy_0.2.wav">
        Your browser does not support the
        <code>audio</code> element.
</audio>　</td>
<td ALIGN=CENTER>　<audio
    controls
    src="inter/our/2ZviHInGBJQ-00031.npyx0nI65jgHG9o-00005.npy_0.2.wav">
        Your browser does not support the
        <code>audio</code> element.
</audio>　</td>
</tr>
<tr>
<td ALIGN=CENTER>　<p>0.3A + 0.7B</p>　</td>
<td ALIGN=CENTER>　<audio
    controls
    src="inter/attn_only/2ZviHInGBJQ-00031.npyx0nI65jgHG9o-00005.npy_0.3.wav">
        Your browser does not support the
        <code>audio</code> element.
</audio>　</td>
<td ALIGN=CENTER>　<audio
    controls
    src="inter/our/2ZviHInGBJQ-00031.npyx0nI65jgHG9o-00005.npy_0.3.wav">
        Your browser does not support the
        <code>audio</code> element.
</audio>　</td>
</tr>
<tr>
<td ALIGN=CENTER>　<p>0.4A + 0.6B</p>　</td>
<td ALIGN=CENTER>　<audio
    controls
    src="inter/attn_only/2ZviHInGBJQ-00031.npyx0nI65jgHG9o-00005.npy_0.4.wav">
        Your browser does not support the
        <code>audio</code> element.
</audio>　</td>
<td ALIGN=CENTER>　<audio
    controls
    src="inter/our/2ZviHInGBJQ-00031.npyx0nI65jgHG9o-00005.npy_0.4.wav">
        Your browser does not support the
        <code>audio</code> element.
</audio>　</td>
</tr>
<tr>
<td ALIGN=CENTER>　<p>0.5A + 0.5B</p>　</td>
<td ALIGN=CENTER>　<audio
    controls
    src="inter/attn_only/2ZviHInGBJQ-00031.npyx0nI65jgHG9o-00005.npy_0.5.wav">
        Your browser does not support the
        <code>audio</code> element.
</audio>　</td>
<td ALIGN=CENTER>　<audio
    controls
    src="inter/our/2ZviHInGBJQ-00031.npyx0nI65jgHG9o-00005.npy_0.5.wav">
        Your browser does not support the
        <code>audio</code> element.
</audio>　</td>
</tr>
<tr>
<td ALIGN=CENTER>　<p>0.6A + 0.4B</p>　</td>
<td ALIGN=CENTER>　<audio
    controls
    src="inter/attn_only/2ZviHInGBJQ-00031.npyx0nI65jgHG9o-00005.npy_0.6.wav">
        Your browser does not support the
        <code>audio</code> element.
</audio>　</td>
<td ALIGN=CENTER>　<audio
    controls
    src="inter/our/2ZviHInGBJQ-00031.npyx0nI65jgHG9o-00005.npy_0.6.wav">
        Your browser does not support the
        <code>audio</code> element.
</audio>　</td>
</tr>
<tr>
<td ALIGN=CENTER>　<p>0.7A + 0.3B</p>　</td>
<td ALIGN=CENTER>　<audio
    controls
    src="inter/attn_only/2ZviHInGBJQ-00031.npyx0nI65jgHG9o-00005.npy_0.7.wav">
        Your browser does not support the
        <code>audio</code> element.
</audio>　</td>
<td ALIGN=CENTER>　<audio
    controls
    src="inter/our/2ZviHInGBJQ-00031.npyx0nI65jgHG9o-00005.npy_0.7.wav">
        Your browser does not support the
        <code>audio</code> element.
</audio>　</td>
</tr>
<tr>
<td ALIGN=CENTER>　<p>0.8A + 0.2B</p>　</td>
<td ALIGN=CENTER>　<audio
    controls
    src="inter/attn_only/2ZviHInGBJQ-00031.npyx0nI65jgHG9o-00005.npy_0.8.wav">
        Your browser does not support the
        <code>audio</code> element.
</audio>　</td>
<td ALIGN=CENTER>　<audio
    controls
    src="inter/our/2ZviHInGBJQ-00031.npyx0nI65jgHG9o-00005.npy_0.8.wav">
        Your browser does not support the
        <code>audio</code> element.
</audio>　</td>
</tr>
<tr>
<td ALIGN=CENTER>　<p>0.9A + 0.1B</p>　</td>
<td ALIGN=CENTER>　<audio
    controls
    src="inter/attn_only/2ZviHInGBJQ-00031.npyx0nI65jgHG9o-00005.npy_0.9.wav">
        Your browser does not support the
        <code>audio</code> element.
</audio>　</td>
<td ALIGN=CENTER>　<audio
    controls
    src="inter/our/2ZviHInGBJQ-00031.npyx0nI65jgHG9o-00005.npy_0.9.wav">
        Your browser does not support the
        <code>audio</code> element.
</audio>　</td>
</tr>
<tr>
<td ALIGN=CENTER>　<p>1.0A + 0.0B</p>　</td>
<td ALIGN=CENTER>　<audio
    controls
    src="inter/attn_only/2ZviHInGBJQ-00031.npyx0nI65jgHG9o-00005.npy_1.wav">
        Your browser does not support the
        <code>audio</code> element.
</audio>　</td>
<td ALIGN=CENTER>　<audio
    controls
    src="inter/our/2ZviHInGBJQ-00031.npyx0nI65jgHG9o-00005.npy_1.wav">
        Your browser does not support the
        <code>audio</code> element.
</audio>　</td>
</tr></tbody></table>
