# FaceVC

This is the demo webpage for the paper 'Face-based Voice Conversion: Learning the Voice behind a Face'.


## Outline

**1. FaceVC demo**

**2. Conversion Interpolation**


## FaceVC demo
<table border="0" cellpadding="0" cellspacing="0" style="width: 100%;">
<tbody>
    <tr>
        <td ALIGN=CENTER valign=CENTER>　<p><b>Speaker photo</b></p>　</td>
        <td ALIGN=CENTER valign=CENTER>　<p><b>FaceVC</b><br>(voice style comes from face)<br>(trained on LRS3 and VCTK)</p>　</td>
        <td ALIGN=CENTER valign=CENTER>　<p><b>AutoVC</b><br>(voice style comes from speech)<br>(trained on LRS3)</p>　</td>
        <td ALIGN=CENTER valign=CENTER>　<p><b>Ground Truth</b></p>　</td>
    </tr>
    <tr>
        <td ALIGN=CENTER>　<img alt="" src="img/male/06M8qY7Q74Y_00015.jpg" width="150"/>　</td>
        <td ALIGN=CENTER VALIGN=CENTER>　<audio
            controls
            id="player"
            src="Gwarp_fixG_MSE_tune1/p333_027.npyx06M8qY7Q74Y-00001.npy.wav">
                Your browser does not support the
                <code>audio</code> element.
        </audio>　</td>
        <td ALIGN=CENTER VALIGN=CENTER>　<audio
            controls
            src="embeds_sound_270085_32_256_512_32_l1loss_lambda1_2280000/p333_027.npyx06M8qY7Q74Y-00001.npy.wav">
                Your browser does not support the
                <code>audio</code> element.
        </audio>　</td>
        <td ALIGN=CENTER VALIGN=CENTER>　<audio
            controls
            src="GT/06M8qY7Q74Y-00001.wav">
                Your browser does not support the
                <code>audio</code> element.
        </audio>　</td>
    </tr>
    <tr>
        <td ALIGN=CENTER>　<img alt="" src="img/male/05jJodDVJRQ_00032.jpg" width="150"/>　</td>
        <td ALIGN=CENTER VALIGN=CENTER>　<audio
            controls
            src="Gwarp_fixG_MSE_tune1/p333_027.npyx05jJodDVJRQ-00002.npy.wav">
                Your browser does not support the
                <code>audio</code> element.
        </audio>　</td>
        <td ALIGN=CENTER VALIGN=CENTER>　<audio
            controls
            src="embeds_sound_270085_32_256_512_32_l1loss_lambda1_2280000/p333_027.npyx05jJodDVJRQ-00002.npy.wav">
                Your browser does not support the
                <code>audio</code> element.
        </audio>　</td>
        <td ALIGN=CENTER VALIGN=CENTER>　<audio
            controls
            src="GT/05jJodDVJRQ-00002.wav">
                Your browser does not support the
                <code>audio</code> element.
        </audio>　</td>
    </tr>
    <tr>
        <td ALIGN=CENTER>　<img alt="" src="img/male/MHN1gqrXMUM_00007.jpg" width="150"/>　</td>
        <td ALIGN=CENTER VALIGN=CENTER>　<audio
            controls
            src="Gwarp_fixG_MSE_tune1/p333_027.npyxMHN1gqrXMUM-00024.npy.wav">
                Your browser does not support the
                <code>audio</code> element.
        </audio>　</td>
        <td ALIGN=CENTER VALIGN=CENTER>　<audio
            controls
            src="embeds_sound_270085_32_256_512_32_l1loss_lambda1_2280000/p333_027.npyxMHN1gqrXMUM-00024.npy.wav">
                Your browser does not support the
                <code>audio</code> element.
        </audio>　</td>
        <td ALIGN=CENTER VALIGN=CENTER>　<audio
            controls
            src="GT/MHN1gqrXMUM-00001.wav">
                Your browser does not support the
                <code>audio</code> element.
        </audio>　</td>
    </tr>
    <tr>
        <td ALIGN=CENTER>　<img alt="" src="img/female/0wpCZxiAQzw_00037.jpg" width="150"/>　</td>
        <td ALIGN=CENTER VALIGN=CENTER>　<audio
            controls
            src="Gwarp_fixG_MSE_tune1/p333_027.npyx0wpCZxiAQzw-00001.npy.wav">
                Your browser does not support the
                <code>audio</code> element.
        </audio>　</td>
        <td ALIGN=CENTER VALIGN=CENTER>　<audio
            controls
            src="embeds_sound_270085_32_256_512_32_l1loss_lambda1_2280000/p333_027.npyx0wpCZxiAQzw-00001.npy.wav">
                Your browser does not support the
                <code>audio</code> element.
        </audio>　</td>
        <td ALIGN=CENTER VALIGN=CENTER>　<audio
            controls
            src="GT/0wpCZxiAQzw-00001.wav">
                Your browser does not support the
                <code>audio</code> element.
        </audio>　</td>
    </tr>
    <tr>
        <td ALIGN=CENTER>　<img alt="" src="img/female/0akiEFwtkyA_00004.jpg" width="150"/>　</td>
        <td ALIGN=CENTER VALIGN=CENTER>　<audio
            controls
            src="Gwarp_fixG_MSE_tune1/p333_027.npyx0akiEFwtkyA-00001.npy.wav">
                Your browser does not support the
                <code>audio</code> element.
        </audio>　</td>
        <td ALIGN=CENTER VALIGN=CENTER>　<audio
            controls
            src="embeds_sound_270085_32_256_512_32_l1loss_lambda1_2280000/p333_027.npyx0akiEFwtkyA-00001.npy.wav">
                Your browser does not support the
                <code>audio</code> element.
        </audio>　</td>
        <td ALIGN=CENTER VALIGN=CENTER>　<audio
            controls
            src="GT/0akiEFwtkyA-00001.wav">
                Your browser does not support the
                <code>audio</code> element.
        </audio>　</td>
    </tr>
    <tr>
        <td ALIGN=CENTER>　<img alt="" src="img/female/0SW0HFy9Et4_00011.jpg" width="150"/>　</td>
        <td ALIGN=CENTER VALIGN=CENTER>　<audio
            controls
            src="Gwarp_fixG_MSE_tune1/p333_027.npyx0SW0HFy9Et4-00001.npy.wav">
                Your browser does not support the
                <code>audio</code> element.
        </audio>　</td>
        <td ALIGN=CENTER VALIGN=CENTER>　<audio
            controls
            src="embeds_sound_270085_32_256_512_32_l1loss_lambda1_2280000/p333_027.npyx0SW0HFy9Et4-00001.npy.wav">
                Your browser does not support the
                <code>audio</code> element.
        </audio>　</td>
        <td ALIGN=CENTER VALIGN=CENTER>　<audio
            controls
            src="GT/0SW0HFy9Et4-00001.wav">
                Your browser does not support the
                <code>audio</code> element.
        </audio>　</td>
    </tr>
</tbody></table>
<br>

<h2>Conversion Interpolation</h2>
Since FaceVC is applied reparamterization trick, speaker embedding can be interpolated. 
Following samples show the interpolated voice style between 2 specified speakers.
<br>
<br>
<table border="0" cellpadding="0" cellspacing="0" style="width: 100%;">
    <tr>
        <td ALIGN=CENTER>　<p>Speaker A</p>　</td>
        <td ALIGN=CENTER>　<p>Speaker B</p>　</td>
    </tr>
    <tr>
        <td ALIGN=CENTER>　<img alt="" src="img/female/0SW0HFy9Et4_00011.jpg"  width="150"/>　</td>
        <td ALIGN=CENTER>　<img alt="" src="img/male/08ZWROqoTZo_00026.jpg"  width="150"/>　</td>
    </tr>
</table>
<br>
<table border="0" cellpadding="0" cellspacing="0" style="width: 100%;">
<tbody>
    <tr>
        <td ALIGN=CENTER valign=CENTER>　<p>Ratio</p>　</td>
        <td ALIGN=CENTER valign=CENTER>　<p>Audio</p>　</td>
    </tr>
    <tr>
        <td ALIGN=CENTER>　<p>0.0A + 1.0B</p>　</td>
        <td ALIGN=CENTER VALIGN=CENTER>　<audio
            controls
            src="Gwarp_fixG_MSE_tune1_inter/p237_086.npyx0SW0HFy9Et4-00002.npy_08ZWROqoTZo-00005.npy_1.0.wav">
                Your browser does not support the
                <code>audio</code> element.
        </audio>　</td>
    </tr>
    <tr>
        <td ALIGN=CENTER>　<p>0.2A + 0.8B</p>　</td>
        <td ALIGN=CENTER VALIGN=CENTER>　<audio
            controls
            src="Gwarp_fixG_MSE_tune1_inter/p237_086.npyx0SW0HFy9Et4-00002.npy_08ZWROqoTZo-00005.npy_0.8.wav">
                Your browser does not support the
                <code>audio</code> element.
        </audio>　</td>
    </tr>
    <tr>
        <td ALIGN=CENTER>　<p>0.4A + 0.6B</p>　</td>
        <td ALIGN=CENTER VALIGN=CENTER>　<audio
            controls
            src="Gwarp_fixG_MSE_tune1_inter/p237_086.npyx0SW0HFy9Et4-00002.npy_08ZWROqoTZo-00005.npy_0.6.wav">
                Your browser does not support the
                <code>audio</code> element.
        </audio>　</td>
    </tr>
    <tr>
        <td ALIGN=CENTER>　<p>0.6A + 0.4B</p>　</td>
        <td ALIGN=CENTER VALIGN=CENTER>　<audio
            controls
            src="Gwarp_fixG_MSE_tune1_inter/p237_086.npyx0SW0HFy9Et4-00002.npy_08ZWROqoTZo-00005.npy_0.4.wav">
                Your browser does not support the
                <code>audio</code> element.
        </audio>　</td>
    </tr>
    <tr>
        <td ALIGN=CENTER>　<p>0.8A + 0.2B</p>　</td>
        <td ALIGN=CENTER VALIGN=CENTER>　<audio
            controls
            src="Gwarp_fixG_MSE_tune1_inter/p237_086.npyx0SW0HFy9Et4-00002.npy_08ZWROqoTZo-00005.npy_0.2.wav">
                Your browser does not support the
                <code>audio</code> element.
        </audio>　</td>
    </tr>
    <tr>
        <td ALIGN=CENTER>　<p>1.0A + 0.0B</p>　</td>
        <td ALIGN=CENTER VALIGN=CENTER>　<audio
            controls
            src="Gwarp_fixG_MSE_tune1_inter/p237_086.npyx0SW0HFy9Et4-00002.npy_08ZWROqoTZo-00005.npy_0.0.wav">
                Your browser does not support the
                <code>audio</code> element.
        </audio>　</td>
    </tr>
</tbody></table>
<br>
<table border="0" cellpadding="0" cellspacing="0" style="width: 100%;">
    <tr>
        <td ALIGN=CENTER>　<p>Speaker C</p>　</td>
        <td ALIGN=CENTER>　<p>Speaker D</p>　</td>
    </tr>
    <tr>
        <td ALIGN=CENTER>　<img alt="" src="img/female/0akiEFwtkyA_00004.jpg"  width="150"/>　</td>
        <td ALIGN=CENTER>　<img alt="" src="img/male/06M8qY7Q74Y_00015.jpg"  width="150"/>　</td>
    </tr>
</table>
<br>
<table border="0" cellpadding="0" cellspacing="0" style="width: 100%;">
<tbody>
    <tr>
        <td ALIGN=CENTER valign=CENTER>　<p>Ratio</p>　</td>
        <td ALIGN=CENTER valign=CENTER>　<p>Audio</p>　</td>
    </tr>
    <tr>
        <td ALIGN=CENTER>　<p>0.0C + 1.0D</p>　</td>
        <td ALIGN=CENTER VALIGN=CENTER>　<audio
            controls
            src="Gwarp_fixG_MSE_tune1_inter/p266_243.npyx0akiEFwtkyA-00001.npy_06M8qY7Q74Y-00001.npy_1.0.wav">
                Your browser does not support the
                <code>audio</code> element.
        </audio>　</td>
    </tr>
    <tr>
        <td ALIGN=CENTER>　<p>0.2C + 0.8D</p>　</td>
        <td ALIGN=CENTER VALIGN=CENTER>　<audio
            controls
            src="Gwarp_fixG_MSE_tune1_inter/p266_243.npyx0akiEFwtkyA-00001.npy_06M8qY7Q74Y-00001.npy_0.8.wav">
                Your browser does not support the
                <code>audio</code> element.
        </audio>　</td>
    </tr>
    <tr>
        <td ALIGN=CENTER>　<p>0.4C + 0.6D</p>　</td>
        <td ALIGN=CENTER VALIGN=CENTER>　<audio
            controls
            src="Gwarp_fixG_MSE_tune1_inter/p266_243.npyx0akiEFwtkyA-00001.npy_06M8qY7Q74Y-00001.npy_0.6.wav">
                Your browser does not support the
                <code>audio</code> element.
        </audio>　</td>
    </tr>
    <tr>
        <td ALIGN=CENTER>　<p>0.6C + 0.4D</p>　</td>
        <td ALIGN=CENTER VALIGN=CENTER>　<audio
            controls
            src="Gwarp_fixG_MSE_tune1_inter/p266_243.npyx0akiEFwtkyA-00001.npy_06M8qY7Q74Y-00001.npy_0.4.wav">
                Your browser does not support the
                <code>audio</code> element.
        </audio>　</td>
    </tr>
    <tr>
        <td ALIGN=CENTER>　<p>0.8C + 0.2D</p>　</td>
        <td ALIGN=CENTER VALIGN=CENTER>　<audio
            controls
            src="Gwarp_fixG_MSE_tune1_inter/p266_243.npyx0akiEFwtkyA-00001.npy_06M8qY7Q74Y-00001.npy_0.2.wav">
                Your browser does not support the
                <code>audio</code> element.
        </audio>　</td>
    </tr>
    <tr>
        <td ALIGN=CENTER>　<p>1.0C + 0.0D</p>　</td>
        <td ALIGN=CENTER VALIGN=CENTER>　<audio
            controls
            src="Gwarp_fixG_MSE_tune1_inter/p266_243.npyx0akiEFwtkyA-00001.npy_06M8qY7Q74Y-00001.npy_0.0.wav">
                Your browser does not support the
                <code>audio</code> element.
        </audio>　</td>
    </tr>
</tbody></table>
