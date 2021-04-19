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
            src="Gwarp_fixG_MSE_tune1/p333_027.npyx06M8qY7Q74Y-00001.npy.wav">
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
        <td ALIGN=CENTER>　<img alt="" src="img/male/08ZWROqoTZo_00026.jpg" width="150"/>　</td>
        <td ALIGN=CENTER VALIGN=CENTER>　<audio
            controls
            src="Gwarp_fixG_MSE_tune1/p333_027.npyx08ZWROqoTZo-00001.npy.wav">
                Your browser does not support the
                <code>audio</code> element.
        </audio>　</td>
        <td ALIGN=CENTER VALIGN=CENTER>　<audio
            controls
            src="GT/08ZWROqoTZo-00001.wav">
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
            src="GT/05jJodDVJRQ-00002.wav">
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
            src="GT/0SW0HFy9Et4-00001.wav">
                Your browser does not support the
                <code>audio</code> element.
        </audio>　</td>
    </tr>
</tbody></table>


## Conversion Interpolation
<table border="0" cellpadding="0" cellspacing="0" style="width: 100%;">
<tbody>
    <tr>
        <td ALIGN=CENTER>　<p>A</p>　</td>
        <td ALIGN=CENTER>　<p>B</p>　</td>
    </tr>
    <tr>
        <td ALIGN=CENTER>　<img alt="" src="img/female/0SW0HFy9Et4_00011.jpg"  width="150"/>　</td>
        <td ALIGN=CENTER>　<img alt="" src="img/male/08ZWROqoTZo_00026.jpg"  width="150"/>　</td>
    </tr>
</tbody></table>


