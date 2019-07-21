# dashboard-template

<h3>Simple Dashboard template.</h3>


Live Demo but not fully accessible:   https://tarun-bisht.github.io/dashboard-template/


<h5>Optimized Dashboard template. Uses Jquery and ajax to optimize and load content of dashboard on flow.</h5>

<b>CANNOT LOAD AJAX IN file:// and github pages SO IT WILL PROMPT ERROR 404. The template should be run on a web server for full experience</b>

<p><h6>Error Prompted without web server</h6>
<code>"cross-origin-requests-are-only-supported-for-http-error-when-loading-a-local" that it cannot load file using ajax.</code></p>

<h3> Methods to start webserver</h3>
<ul>
	<li>
		<h4>Step 1 :</h4>
		<p> First open terminal inside cloned directory </p>
	</li>
	<li>
		<h4>Step 2 :</h4>
		<p> Now type the command below on the basis of installed package</p>
		<ul>
			<li>
			<h4> Python 2 :</h4>
			<p> <code>python -m SimpleHTTPServer </code></p>
			</li>
			<li>
			<h4> Python 3 :</h4>
			<p> <code>python3 -m http.server </code></p>
			</li>
			<li>
			<h4> Nodejs :</h4>
			<p> 
			First install http-server  <code>npm install -g http-server</code><br>
			<code>http-server -c-1 </code></p>
			</li>
			<li>
			<h4> Ruby :</h4>
			<p> 
			<code>ruby -run -e httpd . -p 8000</code></p>
			</li>
			<li>
			<h4> php :</h4>
			<p> 
			<code>php -S localhost:8000</code></p>
			</li>
		</ul>
	</li>
	<li>
		<h4>Step 3 :</h4>
		<p> Type url on browser which is shown in terminal </p>
	</li>
</ul>