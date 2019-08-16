---
layout: default
title: Jvm-Brotli - Lightweight, cross-platform Java library for the Brotli compression format
navlogo: false
permalink: /
---

<style>
{% include landing.css %}
{% include widthOverride.css %}
</style>

<div class="landing blackpart first">
    <div class="center">
		<br/>
		<br/>
		<br/>
		<img src="/img/jvm-brotli.png" alt="Jvm-Brotli" style="width:200px;height:200px;">
		<br/>
		<br/>
		<br/>
		<br/>
		<h1>Lightweight, cross-platform Java library<br/>for the Brotli compression format</h1>
		<a class="landing-btn" href="https://github.com/nixxcode/jvm-brotli"><strong>View on GitHub</strong></a>
    </div>
</div>

<div class ="landing whitepart">
	<h1>Why use Jvm-Brotli?</h1>
	<div class="boxes">
		<div class="box">
			<h3>Quality code</h3>
			<p>
				Up-to-date Brotli code is taken directly from the hard-working team at Google.
			</p>
		</div>
		<div class="box">
			<h3>Easy to use</h3>
			<p>
				Getting Brotli in your Java application is as easy as adding a single Maven dependency.
			</p>
		</div>
		<div class="box">
			<h3>Cross-platform</h3>
			<p>
				Jvm-Brotli already supports Windows, Linux and Mac OSX. More systems coming soon.
			</p>
		</div>
		<div class="box">
			<h3>No C/C++</h3>
			<p>
				Handles the cross-platform compiling of C/C++ code, so you don't have to.
			</p>
		</div>
		<div class="box">
			<h3>Semantic versioning</h3>
			<p>
				Adheres to <a href="https://semver.org">semver</a>, meaning updates won't break your code unexpectedly.
			</p>
		</div>
		<div class="box">
			<h3>Active</h3>
				Both the project and this website are receiving regular updates.

		</div>
	</div>
</div>

<div class="landing blackpart">
	<h1>Adding Jvm-Brotli to your project is easy</h1>
	{% include macros/jvmbrotliMavenDep.md %}
	<div class="center">
		<p>
			We have some code samples and a fully functional example project to get you started:
		</p>
		<a class="landing-btn" href="/examples"><strong>Show code samples</strong></a>
		<a class="landing-btn" href="https://github.com/nixxcode/jvm-brotli-example"><strong>Show example project</strong></a>
	</div>
</div>

<div class="landing whitepart">
    <div class="container-width-limit">
		<h1>What is the purpose of Jvm-Brotli?</h1>
		<p>
			Making Brotli usable in Java can be a tricky and time consuming exercise. The Brotli code is written in c/c++ and is platform dependent. This requires the use of JNI bindings.
		</p>

		<p>
			The bindings are provided by Google, but it is still left to the Java developer to compile the source files individually for every platform they wish to support. Anybody who has dealt with JNI and native code in the past will already be familiar with the problems and complexity this approach can add to a project.
		</p>
		
		<p>
			<strong>The purpose of Jvm-Brotli is to remove the headaches of dealing with JNI. It aims to make Brotli readily available and easy to access for Java developers on as many platforms as possible.</strong>
		</p>
    </div>
</div>