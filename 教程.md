![image](https://github.com/linlabscau/linlabscau.github.io/assets/147996306/e1b2c0c2-3d60-4bec-8e11-3f27dc9c23bf)![image](https://github.com/linlabscau/linlabscau.github.io/assets/147996306/d402b02b-9d96-4cb3-babb-0db56051956e)# linlabscau.github.io
1.如何修改对应的学生简介：
一共有4个地方需要修改；
1）
首先打开member.html文件
发现有这么一段代码：
<div class="member col col-md-2">
			  <img src="image/tx.jpg" alt="成员1">
			  <h2>Researcher</h2>
			  <h2><a style="color: inherit;" href="jhp.html">Dr. JinHuan Pang</a></h2>
			  <p>成员1的简介</p>
</div> 
第一个 Researcher 代表的是在岗位/身份（英文）
第二个 Dr. JinHuan Pang 是具体的名字
第三个 成员1的简介 是具体介绍
第四个  <img src="image/tx.jpg" alt="成员1"> 中的 image/tx.jpg是代表头像的路径
前三处地方都是可以直接修改，第四个要先上传文件到image文件夹，然后把图片的名字替换掉tx.jpg。

2）打开 member-cn.html 文件
发现有这么一段代码；
<div class="member col col-md-2">
				<img src="image/tx.jpg" alt="成员1">
				<h2>实验师</h2>
				<h2><a style="color: inherit;" href="pjh-cn.html">庞金环 博士</a></h2>
				<p>成员1的简介</p>
</div>
修改的方式和1）一致，但是要注意修改的内容是中文。

3.注意步骤1）中出现jhp.html这个文件名，这是对应学生的详细页面文件，打开后按需找代码：
1）修改头像：
<div class="col col-md-4">
					<div class="member-portrait">
						<img src = "image/tx.jpg">
					</div>
</div>
找类似的代码，修改tx.jpg
2）修改工作经历：
<br><h2>Work Experience</h2>                                                                     
					<ul>
						<li>2023, Professor at South China Agricultural University </li>
</ul><br>
3）修改教育经历：
<h2>Education</h2>
					<ul>
						<li>2017-2021	PhD in Genetics, Institute of Genetics and Developmental Biology, Chinese Academy of Sciences
						<li>2014-2017	M.Sc. in Botany, School of Life Science, South China Normal University</li>
						<li>2010-2014	B.Sc. in Life Science (Xiangqin Class), School of Life Science, South China Normal University</li>
					</ul><br>
4）修改获奖荣誉：
					<h2>Honors and Awards</h2>
					<ul>
						<li>2021	Awarded Fellowship of China National Postdoctoral Program for Innovative Talents, 2021</li>
						<li>2020	Awarded National scholarship for doctoral students, 2020</li>
						<li>2020	Awarded President Excellence Scholarship of Chinese Academy of Sciences, 2020 </li>
						<li>2020	Awarded Zhensheng Scholarship, 2020</li>
					</ul>
4.和步骤3一致，但是注意对应的页面是步骤2中的pjh-cn.html

