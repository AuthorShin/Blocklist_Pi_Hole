# Blocklist Pi Hole


<p dir="auto">In this repository you will find my custom blocklists for the PiHole service (Pi-hole is an application for blocking ads and trackers on the Internet that acts as a DNS sink). You can even use them in similar services, AdGuard, Ublock...
<br><br></p>
<h2 dir="auto"><a id="user-content-porque-estas-listas-dns-" class="anchor" aria-hidden="true" href="#porque-estas-listas-dns-"><svg class="octicon octicon-link" viewbox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Why these DNS lists <g-emoji class="g-emoji" alias="mag" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f50d.png">🔍</g-emoji></h2>
<p dir="auto">This project aims to unify the DNS blocking lists by adding my contributions, eliminating false positives, keeping them error-free and optimized. I invite you to help me in this task.
<br><br></p>
<h2 dir="auto"><a id="user-content-detalles-de-las-listas-de-bloqueo-" class="anchor" aria-hidden="true" href="#detalles-de-las-listas-de-bloqueo-"><svg class="octicon octicon-link" viewbox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Details of the blocklists <g-emoji class="g-emoji" alias="book" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f4d6.png">📖</g-emoji></h2>
<table>
<thead>
<tr>
<th align="center">Name of the list</th>
<th align="center">Brief description</th>
<th align="center">Number of entries</th>
<th align="center">RAW</th>
</tr>
</thead>
<tbody>
<tr>
<td align="center">Ads and trackers</td>
<td align="center">Block advertisements and trackers</td>
<td align="center">675,276</td>
<td align="center"><a href="https://raw.githubusercontent.com/AuthorShin/Blocklist_Pi_Hole/master/Ads%20and%20trackers.txt" rel="nofollow">list</a></td>
</tr>
<tr>
<td align="center">Mining pages</td>
<td align="center">Block mining pages and services</td>
<td align="center">34,539</td>
<td align="center"><a href="https://raw.githubusercontent.com/AuthorShin/Blocklist_Pi_Hole/master/Mining%20pages.txt" rel="nofollow">list</a></td>
</tr>
<tr>
<td align="center">Pages with porn</td>
<td align="center">Block pages with XXX content</td>
<td align="center">2,048,596</td>
<td align="center"><a href="https://raw.githubusercontent.com/AuthorShin/Blocklist_Pi_Hole/master/Porn%20pages.txt" rel="nofollow">list</a></td>
</tr>
<tr>
<td align="center">Xiaomi  Mi-Fit  Amazfit  Huami</td>
<td align="center">COMPLETE blocking of any connection</td>
<td align="center">1,076</td>
<td align="center"><a href="https://raw.githubusercontent.com/AuthorShin/Blocklist_Pi_Hole/master/Xiaomi%20Mi-Fit%20Amazfit%20Huami.txt" rel="nofollow">list</a></td>
</tr>
<tr>
<td align="center">Windows telemetry</td>
<td align="center">Block all Windows OS telemetry</td>
<td align="center">1,012</td>
<td align="center"><a href="https://raw.githubusercontent.com/AuthorShin/Blocklist_Pi_Hole/master/Windows%20telemetry.txt" rel="nofollow">list</a></td>
</tr>
<tr>
<td align="center">Iran TLD and websites that host inside the IRAN</td>
<td align="center">Block all inside Iran hosted websites (mostly IR TLD)</td>
<td align="center">28,367</td>
<td align="center"><a href="https://raw.githubusercontent.com/AuthorShin/Blocklist_Pi_Hole/master/IR-domains.txt" rel="nofollow">list</a></td>
</tr>
<tr>
<td align="center">Some ad domain that were missing from https://d3ward.github.io/toolz/adblock test</td>
<td align="center">Block the remaining ad services of Google Ads Doubleclick.net Amazon FreshMarketer Bugsnag Sentry Facebook Twitter Pinterest Reddit YouTube TikTok Yandex Xiaomi Huawei OnePlus Samsung Apple</td>
<td align="center">103</td>
<td align="center"><a href="https://raw.githubusercontent.com/AuthorShin/Blocklist_Pi_Hole/master/etc.txt" rel="nofollow">list</a></td>
</tr>
<tr>
<td align="center">DoT & DoH & traditional DNS servers</td>
<td align="center">Block DoT, DoH & traditional DNS servers to prevent bypassing pihole</td>
<td align="center">559</td>
<td align="center"><a href="https://raw.githubusercontent.com/AuthorShin/Blocklist_Pi_Hole/main/DoT_DoH_traditional_DNS_servers.txt" rel="nofollow">list</a></td>
</tr>
</tbody>
</table>
<br>
<h2 dir="auto"><a id="user-content-pre-requisitos-" class="anchor" aria-hidden="true" href="#pre-requisitos-"><svg class="octicon octicon-link" viewbox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Pre-requisites <g-emoji class="g-emoji" alias="clipboard" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f4cb.png">📋</g-emoji></h2>
<p dir="auto">You only need to have the Pi-Hole service installed, you can do it in the terminal with the following command:</p>
<p dir="auto"><code>curl -sSL https://install.pi-hole.net | bash</code>
<br><br></p>
<h2 dir="auto"><a id="user-content-descargo-de-responsabilidad-" class="anchor" aria-hidden="true" href="#descargo-de-responsabilidad-"><svg class="octicon octicon-link" viewbox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Disclaimer <g-emoji class="g-emoji" alias="rotating_light" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f6a8.png">🚨</g-emoji></h2>
<p dir="auto">This blocklists are hosts files to block access to domains / websites. If you don't know how it works, please read the installation and usage section. Try this at your own risk, I am not responsible for any damage, loss or problems caused.
<br><br></p>
<h2 dir="auto"><a id="user-content-licencia-" class="anchor" aria-hidden="true" href="#licencia-"><svg class="octicon octicon-link" viewbox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>License<g-emoji class="g-emoji" alias="page_facing_up" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f4c4.png">📄</g-emoji></h2>
  <div class="mt-2">
    <a href="https://github.com/AuthorShin/Blocklist_Pi_Hole/blob/master/LICENSE" class="Link--muted">
     MIT License
    </a>
  </div>
</article>
