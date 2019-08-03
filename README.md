<h1><span style="text-decoration: underline;">CircleImageView&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;</span></h1>
<p><span style="font-size: 12pt;">A fast CompassImageView perfect for Round Images in Android.&nbsp;</span></p>
<p><span style="text-decoration: underline;"><strong><span style="font-size: 14pt;">Usage</span></strong></span></p>
<p><span style="font-size: 12pt;">Add it in your root build.gradle at the end of repositories:</span></p>
<pre class="kode language-css code-toolbar"><code class=" kode language-css">	<span class="token selector">allprojects</span> <span class="token punctuation">{</span>
		<span class="token selector">repositories</span> <span class="token punctuation">{</span>
			<span class="token selector">...
			maven</span> <span class="token punctuation">{</span> url <span class="token string">'https://jitpack.io'</span> <span class="token punctuation">}</span>
		<span class="token punctuation">}</span>
	<span class="token punctuation">}</span></code></pre>
<p>&nbsp;</p>
<p>Add the <span style="font-size: 12pt;">dependency</span></p>
<pre class="kode code-toolbar  language-css"><code id="depCodeGradle" class=" kode  language-css"><span class="token selector">dependencies</span> <span class="token punctuation">{</span>
	        implementation <span class="token string">'com.github.mammahe:CompassImageView:a15953d0b7'</span>
	<span class="token punctuation">}</span></code></pre>
<p><span style="font-size: 12pt; font-family: verdana, geneva;">Add it in your res/activity_main.xml as shown below</span></p>
<pre>&lt;com.sairamkrishna.compassimageview.CompassImageView<br />    android:layout_width="200dp"<br />    android:layout_height="200dp"<br />    android:src="@drawable/musk"<br />  <span style="color: #ff0000;">  app:image_background_color="#FF000000"</span><br /><span style="color: #ff0000;">    app:image_border_color="#B22222"</span><br />    app:image_border_width="2dp"<br />    app:layout_constraintBottom_toBottomOf="parent"<br />    app:layout_constraintEnd_toEndOf="parent"<br />    app:layout_constraintHorizontal_bias="0.5"<br />    app:layout_constraintStart_toStartOf="parent"<br />    app:layout_constraintTop_toTopOf="parent"<br />    tools:ignore="MissingConstraints" /&gt;</pre>
<h2>Output</h2>
<p><img src="https://github.com/mammahe/CompassImageView/blob/master/Screenshot_20190803-152530.png" alt="" width="350" height="600" /></p>
<h2>License</h2>
<p>Copyright 2019 Sairamkrishna Mammahe</p>
<p>Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at</p>
<p><a href="http://www.apache.org/licenses/LICENSE-2.0" rel="nofollow">http://www.apache.org/licenses/LICENSE-2.0</a></p>
<p>Unless required by applicable law or agreed to in writing, software under the License is distributed on an "AS IS" BASIS, WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. the License for the specific language governing permissions and under the License.</p>
