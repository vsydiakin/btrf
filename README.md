<h1 class="code-line" data-line-start=0 data-line-end=1 ><a id="DynamoDb_autopopulation_tool_0"></a>DynamoDb autopopulation tool</h1>
<p class="has-line-data" data-line-start="2" data-line-end="3">This tools takes clients ids from DynamoDb and check clients from Cognito then updates missing clients.</p>
<ul>
<li class="has-line-data" data-line-start="4" data-line-end="5">Type some Markdown on the left</li>
<li class="has-line-data" data-line-start="5" data-line-end="6">See HTML in the right</li>
<li class="has-line-data" data-line-start="6" data-line-end="8">Magic</li>
</ul>
<h2 class="code-line" data-line-start=8 data-line-end=9 ><a id="Getting_Started_8"></a>Getting Started</h2>
<p class="has-line-data" data-line-start="9" data-line-end="10">These instructions will get you steps how to use this tool.</p>
<h3 class="code-line" data-line-start=11 data-line-end=12 ><a id="Prerequisites_11"></a>Prerequisites</h3>
<p class="has-line-data" data-line-start="12" data-line-end="13">To use this tools you need to install:</p>
<ul>
<li class="has-line-data" data-line-start="13" data-line-end="14">argparse</li>
<li class="has-line-data" data-line-start="14" data-line-end="15">boto3</li>
<li class="has-line-data" data-line-start="15" data-line-end="16">coloredlogs</li>
<li class="has-line-data" data-line-start="16" data-line-end="18">prettytable</li>
</ul>
<p class="has-line-data" data-line-start="18" data-line-end="19">How to install:</p>
<pre><code class="has-line-data" data-line-start="20" data-line-end="23" class="language-sh">$ <span class="hljs-built_in">cd</span> ./wd_cloud/iac/scripts
$ pip3 install requirements.txt
</code></pre>
<p class="has-line-data" data-line-start="23" data-line-end="24">or you can install it separately:</p>
<pre><code class="has-line-data" data-line-start="25" data-line-end="30" class="language-sh">$ pip3 install argparse
$ pip3 install boto3
$ pip3 install coloredlogs
$ pip3 install prettytable
</code></pre>
<h3 class="code-line" data-line-start=31 data-line-end=32 ><a id="How_to_use_it_31"></a>How to use it</h3>
<p class="has-line-data" data-line-start="32" data-line-end="33">To use this tool you need:</p>
<pre><code class="has-line-data" data-line-start="34" data-line-end="36" class="language-sh">$ python cognito_client_mapping.py
</code></pre>
