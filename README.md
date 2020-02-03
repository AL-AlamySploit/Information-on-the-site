# Information on the site
#This only for testing

# <Installation
<div class="highlight highlight-source-shell"><pre>git clone https://github.com/AL-AlamySploit/Information-on-the-site
<span class="pl-c1">cd</span> Information-on-the-site
pip3 install -r requirements.txt</pre></div>
<h2><a id="user-content-usage" class="anchor" aria-hidden="true" href="#usage"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Usage</h2>
<div class="highlight highlight-source-shell"><pre>python3 finalrecon.py -h
usage: finalrecon.py [-h] [--headers] [--sslinfo] [--whois] [--crawl] [--full]
                     url

FinalRecon - OSINT Tool <span class="pl-k">for</span> All-In-One Web Recon <span class="pl-k">|</span> v1.0.0

positional arguments:
  url         Target URL

optional arguments:
  -h, --help  show this <span class="pl-c1">help</span> message and <span class="pl-c1">exit</span>
  --headers   Get Header Information
  --sslinfo   Get SSL Certificate Information
  --whois     Get Whois Lookup
  --crawl     Crawl Target Website
  --full      Get Full Analysis, Test All Available Options</pre></div>
<div class="highlight highlight-source-shell"><pre><span class="pl-c"><span class="pl-c">#</span> Check headers</span>

python3 finalrecon.py --headers <span class="pl-k">&lt;</span>url<span class="pl-k">&gt;</span>

<span class="pl-c"><span class="pl-c">#</span> Check ssl Certificate</span>

python3 finalrecon.py --sslinfo <span class="pl-k">&lt;</span>url<span class="pl-k">&gt;</span>

<span class="pl-c"><span class="pl-c">#</span> Check whois Information</span>

python3 finalrecon.py --whois <span class="pl-k">&lt;</span>url<span class="pl-k">&gt;</span>

<span class="pl-c"><span class="pl-c">#</span> Crawl Target</span>

python3 finalrecon.py --crawl <span class="pl-k">&lt;</span>url<span class="pl-k">&gt;</span>

<span class="pl-c"><span class="pl-c">#</span> full scan</span>

python3 finalrecon.py --full <span class="pl-k">&lt;</span>url<span class="pl-k">&gt;</span></pre></div>
<h2><a id="user-content-demo" class="anchor" aria-hidden="true" href="#demo"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Demo</h2>
<p><a href="https://www.youtube.com/watch?v=5s0ghojbUtQ" rel="nofollow"><img src="https://camo.githubusercontent.com/24b86cc612c681910ac9d3993016a3e43281a6dc/68747470733a2f2f692e696d6775722e636f6d2f6a593056366c6e2e706e67" alt="Youtube" data-canonical-src="https://i.imgur.com/jY0V6ln.png" style="max-width:100%;"></a></p>
</article>
