# Information on the site
#This only for testing

# <Installation
<div class="highlight highlight-source-shell"><pre>git clone https://github.com/AL-AlamySploit/Information-on-the-site
<span class="pl-c1">cd</span> Information-on-the-site
pip3 install -r requirements.txt</pre></div>


<div class="highlight highlight-source-shell"><pre>python3 Information.py -h
usage: Information.py [-h] [--headers] [--sslinfo] [--whois] [--crawl] [--full]
                     url

Information on the site - OSINT Tool <span class="pl-k">for</span> All-In-One Web Recon <span class="pl-k">|</span> v1.0.0

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

python3 Information.py --headers <span class="pl-k">&lt;</span>url<span class="pl-k">&gt;</span>

<span class="pl-c"><span class="pl-c">#</span> Check ssl Certificate</span>

python3 Information.py --sslinfo <span class="pl-k">&lt;</span>url<span class="pl-k">&gt;</span>

<span class="pl-c"><span class="pl-c">#</span> Check whois Information</span>

python3 Information.py --whois <span class="pl-k">&lt;</span>url<span class="pl-k">&gt;</span>

<span class="pl-c"><span class="pl-c">#</span> Crawl Target</span>

python3 Information.py --crawl <span class="pl-k">&lt;</span>url<span class="pl-k">&gt;</span>

<span class="pl-c"><span class="pl-c">#</span> full scan</span>

python3 Information.py --full <span class="pl-k">&lt;</span>url<span class="pl-k">&gt;</span></pre></div></a></p></article>
