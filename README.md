# INDIANARMYPROJECT--TinyYolo
<head>
    <link rel="stylesheet" href="style.css">
    <meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
</head>
<p align = "center"><img src="C:\Users\ANIKET\Desktop\webd assign\iiita1.jpg" alt="iiita" style="width:100px;height:100px;"/></p>
<h1 style="background-color: rgb(158, 231, 255); color: red;"align="center">INDIAN INSTITUTE OF INFORMATION TECHNOLOGY, ALLAHABAD</h1>

<h3 align="center">PROPOSED FOR: INDIAN ARMY - LADAKH SCOUTS</h3>
<h2 style="color:red;" align="center"> HUMAN FOLLOWING BOT</h2>

<p align="left"> <img src="https://komarev.com/ghpvc/?username=iiitprayagraj&label=Profile%20views&color=0e75b6&style=flat" alt="iiitprayagraj" /> </p>
<p align="center"> <img src="C:\Users\ANIKET\Desktop\webd assign\MOT_poster.png" alt="iiitprayagraj" height = "700" width = "900" /> </p>



<h2>DESCRIPTION: </h2>
<ul>
    <li>Max speed as catered in your design is 21kmph.    </li>
    <li>Min speed can be brought to 2 Km/ Hr.    </li>
    <li> ⁠Min distance covered in single charge(70 Km) will cater for our requirements.</li>
    <li>Average wind Speed : 1.4 m/s ( Max Speed 6 m/s)    </li>
    <li>Max payload weight of 120Kg.    </li>
    <li>Independent articulation & independent suspension to be given to wheels.    </li>
    <li>Design has been considered keeping in view the fact that it has to be used in combat environment.</li>
    <li>GROUND CLEARENCE: Wheel Clearance: 4 inches.    </li>
    <li> Suspension Clearance: 3inches.</li>
</ul>

<h3>Technologies used for object detection:       YOLO V7</h3>
<p>The  <b>YOLO v7 model </b> is the latest in the family of YOLO models. YOLO models are single stage object detectors. In a YOLO model, <i>image frames are featurized through a backbone</i>. These features are combined and mixed in the neck, and then they are passed along to the head of the network YOLO predicts the locations and classes of objects around which bounding boxes should be drawn.</p>
<p>YOLOv7 is a <b>state-of-the-art real-time object detector</b> that surpasses all known object detectors in both <b>speed and accuracy</b> in the <i>range from 5 FPS to 160 FPS</i>. It has<b> the highest accuracy (56.8% AP)</b> among all known real-time object detectors with 30 FPS or higher on GPU V100. Moreover, YOLOv7 outperforms other object detectors such as YOLOR, YOLOX, Scaled-YOLOv4, YOLOv5, and many others in speed and accuracy.</p>

   
 <strong>YOLOv7 introduces several key features:</strong>
 <ol>
<li>
<strong>Model Re-parameterization:</strong> YOLOv7 proposes <i>a planned re-parameterized model</i>, which is a strategy applicable to layers in different networks with the concept of gradient propagation path.
</li>
<br>
<li>
    <strong>Dynamic Label Assignment:</strong> The training of the model with multiple output layers presents a new issue: "How to assign dynamic targets for the outputs of different branches?" To solve this problem, YOLOv7 introduces <i>a new label assignment method called coarse-to-fine</i> lead guided label assignment.
</li><br>
<li>
    <strong>Extended and Compound Scaling:</strong> YOLOv7 proposes <i>"extend" and "compound scaling" methods</i> for the real-time object detector that can effectively utilize parameters and computation.
</li>
<br>
<li>
    <strong>Efficiency:</strong> The method proposed by YOLOv7 can effectively <i>reduce about 40% parameters and 50% computation of state-of-the-art real-time object detector</i>, and has faster inference speed and higher detection accuracy.
</li>
<h3>COMPARISON DESCRIPTION: </h3>
<p align="left"> <img src="https://github-production-user-asset-6210df.s3.amazonaws.com/26833433/245965939-5e1e0420-8122-4c79-b8d0-2860aa79af92.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAVCODYLSA53PQK4ZA%2F20240420%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240420T184906Z&X-Amz-Expires=300&X-Amz-Signature=efe59426daceafff923ccc3af3b5b54cfca327cffba46cd70668894a098cdbc3&X-Amz-SignedHeaders=host&actor_id=158501469&key_id=0&repo_id=535360445" alt="iiitprayagraj" width="800" height="500"/> </p>
<p><h3>
<b>Comparison of state-of-the-art object detectors: </b>
</h3>
<p>
 From the results we know that the proposed method has<b> the best speed-accuracy trade-off comprehensively</b>. If we compare YOLOv7-tiny-SiLU with YOLOv5-N (r6.1), <b>our method is 127 fps faster and 10.7% more accurate on AP</b>. In addition, <b>YOLOv7 has 51.4% AP at frame rate of 161 fps</b>, while PPYOLOE-L with the same AP has only 78 fps frame rate. In terms of parameter usage, <b>YOLOv7 is 41% less than PPYOLOE-L</b>. If we compare YOLOv7-X with 114 fps inference speed to YOLOv5-L (r6.1) with 99 fps inference speed,<b> YOLOv7-X can improve AP by 3.9%.</b> If YOLOv7-X is compared with YOLOv5-X (r6.1) of similar scale, <b>the inference speed of YOLOv7-X is 31 fps faster.</b> In addition, in terms the amount of parameters and computation, <b>YOLOv7-X reduces 22% of parameters and 8% of computation compared to YOLOv5-X (r6.1), but improves AP by 2.2%.</b>

</p>
