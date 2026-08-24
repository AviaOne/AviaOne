<div align="center">

<h1>AVIAONE.com 🟢 Since 2021</h1>

<img src="https://aviaone.com/blog/wp-content/uploads/2022/09/cropped-header-background-black-aviaone.jpg" width="300">

<h3><b><i>W E &nbsp; ARE &nbsp; P R O F E S S I O N A L &nbsp; V A L I D A T O R S &nbsp; 24/7 &nbsp; S P E C I A L I Z E D<br />I N &nbsp; T H E &nbsp; C O S M O S &nbsp; E C O S Y S T E M.</b></i></h3>

</div>

<hr>

<div align="center"><h2><b>M A I N N E T S</b></h2></div>

<table width="320px" align="center">
    <tbody>
        <tr valign="top">
            <td width="130px" align="center">
            <span><strong>ATOMONE</strong></span><br><br />
            <a href="https://restake.app/atomone/atonevaloper1342p4lqh94s8qrk48vz2x6nlh3p2hqx4autnd9" target="_blank" rel="noopener noreferrer">
            <img height="60px" src="https://raw.githubusercontent.com/cosmos/chain-registry/master/atomone/images/atomone.png"></a>
            </td>
            <td width="130px" align="center">
            <span><strong>FETCH</strong></span><br><br />
            <a href="https://aviaone.com/fetch-blockchain-ai" target="_blank" rel="noopener noreferrer">
            <img height="60px" src="https://pbs.twimg.com/profile_images/1807887745358221319/oC9VurEz_400x400.jpg"></a>
            </td>
            <td width="130px" align="center">
            <span><strong>GNO.LAND</strong></span><br><br />
            <a href="https://github.com/gnolang" target="_blank" rel="noopener noreferrer">
            <img height="60px" src="https://avatars.githubusercontent.com/u/75237105?s=200&v=4"></a>
            </td>
        </tr>
    </tbody>
</table>

<div align="center">
<h3>🔗<a href="https://aviaone.com/blog/2024-has-been-a-challenging-year/">Read why we have shutdown 12 mainnets nodes at the end of 2024 ! ↗️</a></h3>
</div>

<hr>

<div align="center">

<h2>🚀 <b>C O N T R I B U T I O N S</b> 🚀</h2>
<p><b>We are very active everywhere and we like to contribute...</b></p>

</div>

<table width="320px" align="center">
    <tbody>
        <tr valign="top">
            <td width="130px" align="center">
            <span><strong>BLOCKCHAINS SERVICE</strong></span><br><br />
            <a href="https://aviaone.com/blockchains-service/" target="_blank" rel="noopener noreferrer">
            <img height="100px" src="https://raw.githubusercontent.com/AviaOne/pictures/main/logo-blockchain-service.png"></a>
            </td>
            <td width="130px" align="center">
            <span><strong>EXPLORER</strong></span><br><br />
            <a href="https://mainnet.explorer.aviaone.com" target="_blank" rel="noopener noreferrer">
            <img height="100px" src="https://raw.githubusercontent.com/AviaOne/pictures/main/generated-logo-explorer2.png"></a>
            </td>
            <td width="130px" align="center">
            <span><strong><a href="https://github.com/AviaOne/tenderseed">TENDERSEED</a></strong></span><br><br />
            <a href="https://github.com/AviaOne/tenderseed/releases/latest">Latest release</a>
            </td>
            <td width="130px" align="center">
            <span><strong><a href="https://github.com/AviaOne/GnoDuty">GNODUTY</a></strong></span><br><br />
            <a href="https://github.com/AviaOne/GnoDuty">TM2 monitoring</a>
            </td>
            <td width="130px" align="center">
            <span><strong><a href="https://github.com/AviaOne/scripts">SCRIPTS</a></strong></span><br><br />
            <a href="https://github.com/AviaOne/scripts">Operator tooling</a>
            </td>
       </tr>
    </tbody>
</table>

<h2>ABS, a permanent contribution to the whole ecosystem</h2>

<p><a href="https://aviaone.com/blockchains-service/"><b>AviaOne BlockChains Service (ABS)</b></a> is our longest running contribution, and the one that never stops: it is maintained every single day.</p>

<p>ABS turns the raw data of the Cosmos Chain Registry into a living dashboard covering <b>more than 350 blockchains</b>, mainnet and testnet alike. It is built for the whole ecosystem, not for our own operations:</p>

<ul>
  <li><b>Verified RPC and API endpoints</b>, tested every 3 hours and sorted by latency, so you never copy a dead endpoint again</li>
  <li><b>Binary version detection</b>: the version actually running on the network, compared against what the registry claims</li>
  <li><b>Block explorers checked every 24 hours</b>, dead links are hidden instead of being served</li>
  <li><b>Live network status</b>: block height, chain IDs, health</li>
  <li>Seeds, peers and installation guides for every listed chain</li>
  <li>Automatic synchronisation with <code>cosmos/chain-registry</code></li>
</ul>

<p>Nobody pays for it and nothing is gated. It exists because validators, developers and node operators need data that is true today, not data that was true when a registry entry was last edited.</p>

<hr>

<h1 align="center">🔧 RECENT TECHNICAL CONTRIBUTIONS 🔧</h1>

<hr>

<p align="center"><b>We do not only run validators, we maintain the software the ecosystem depends on.</b></p>

<h2>Tenderseed, back in maintenance</h2>

<p>Seed nodes are the front door of every Cosmos chain, and the reference implementation had been left unmaintained for more than three years. We took it over.</p>

<p><a href="https://github.com/AviaOne/tenderseed"><b>AviaOne/tenderseed</b></a> is maintained and released regularly, under the original Blue Oak licence:</p>

<p><a href="https://github.com/AviaOne/tenderseed/releases/latest"><img src="https://img.shields.io/github/v/release/AviaOne/tenderseed?label=latest%20release&color=orange"></a></p>

<ul>
  <li>ported to <b>CometBFT v0.40.x</b>, down to 30 compiled dependencies</li>
  <li><b>address verification</b>: every address served to a peer is dialled and qualified first, so the address book stops handing out dead endpoints</li>
  <li>exposed settings that were hardcoded upstream, including <code>seed_disconnect_wait_period</code>, which silently kept every address book almost empty in the original binary and in all of its forks</li>
  <li>Prometheus metrics, unit tests, CI, release archives and multi-arch images on <code>ghcr.io/aviaone/tenderseed</code></li>
  <li>no panics left, existing installations upgrade without touching <code>node_key.json</code></li>
</ul>

<p>Credit where it is due: <a href="https://github.com/BitCannaGlobal/tenderseed">BitCannaGlobal</a> for the earlier port attempt, and <a href="https://github.com/voluzi/cosmoseed">cosmoseed</a> for the composed reactor design.</p>

<h2>Upstream work on gno.land / Tendermint2</h2>

<table>
  <tr>
    <td><a href="https://github.com/gnolang/gno/issues/5340">gnolang/gno#5340</a></td>
    <td>Reported that <code>config.P2P.Seeds</code> was declared but never consumed by TM2.</td>
  </tr>
  <tr>
    <td><a href="https://github.com/gnolang/gno/pull/6023">gnolang/gno#6023</a></td>
    <td>Wired seeds into the switch, with a dedicated dial loop, tests and an ADR. <b>Merged.</b></td>
  </tr>
  <tr>
    <td><a href="https://github.com/gnolang/gno/pull/6054">gnolang/gno#6054</a></td>
    <td>Reviewed and reported a missing test case, adopted upstream in <a href="https://github.com/gnolang/gno/pull/6067">#6067</a>.</td>
  </tr>
  <tr>
    <td><a href="https://github.com/AviaOne/GnoDuty">GnoDuty</a></td>
    <td>Validator monitoring for TM2 networks.</td>
  </tr>
</table>

<hr>

<div align="center">
<h2>🛠 <b>TECHNICAL REPORT AND DETAILS</b> 🛠</h2>
<br />
Our servers are not shared servers, our servers are dedicated server working only for Aviaone to get the best performance for our nodes. They are hosted in one datacenter located in Falkenstein, Germany, in a secure place. Of course, our servers are made accessible only to Aviaone and nobody else can have access to it. We only use high grade servers with CPU : AMD Ryzen™ 7 3700X | RAM : 64 GB DDR4 ECC | Fast Hard drive Mvme 2 X 1 TB with Raid 1.

Everything is monitored 24/7, the slightest details are directly reported and immediately solved.
Proud to be among the validators with the best practices and without any missing block but also active in all circumstances.

We are audited 24/7 by external and independent services.
</div>

<hr>

<div align="center">

<h2>📣 <b>M A R K E T I N G</b> 📣</h2>
<h3>We are actively working to write new articles and tweets regularly and follow the news of the blockchains on which we are validators</h3>
<h3>🔗<a href="https://aviaone.com/blog/">Read our blog ↗️</a></h3>
<h3>🔗<a href="https://twitter.com/avia_one">Follow us on X to see our last news</a></h3>

</div>

<hr>

<div align="center">

<h2>🔗 <b>Links</b> 🔗 </h2>

<table width="320px" align="center">
    <tbody>
        <tr valign="top">
            <td width="130px" align="center">
            <span><strong>Website</strong></span><br><br />
            <a href="https://aviaone.com" target="_blank" rel="noopener noreferrer">
            <img height="40px" src="https://raw.githubusercontent.com/AviaOne/pictures/main/logo-Aviaone--orange-noir512.jpg"></a>
            </td>
            <td width="130px" align="center">
            <span><strong>Youtube</strong></span><br><br />
            <a href="https://www.youtube.com/aviaone" target="_blank" rel="noopener noreferrer">
            <img height="40px" src="https://upload.wikimedia.org/wikipedia/commons/thumb/0/09/YouTube_full-color_icon_%282017%29.svg/159px-YouTube_full-color_icon_%282017%29.svg.png"></a>
            </td>
            <td width="130px" align="center">
            <span><strong>Twitter</strong></span><br><br />
            <a href="https://twitter.com/avia_one" target="_blank" rel="noopener noreferrer">
            <img height="40px" src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/6f/Logo_of_Twitter.svg/150px-Logo_of_Twitter.svg.png"></a>
            </td>
            <td width="130px" align="center">
            <span><strong>Telegram</strong></span><br><br />
            <a href="https://t.me/aviaone" target="_blank" rel="noopener noreferrer">
            <img height="40px" src="https://upload.wikimedia.org/wikipedia/commons/thumb/8/82/Telegram_logo.svg/512px-Telegram_logo.svg.png"></a>
            </td>
            <td width="130px" align="center">
            <span><strong>Keybase</strong></span><br><br />
            <a href="https://keybase.io/aviaone" target="_blank" rel="noopener noreferrer">
            <img height="40px" src="https://upload.wikimedia.org/wikipedia/commons/thumb/b/bb/Keybase_logo_official.svg/640px-Keybase_logo_official.svg.png"></a>
            </td>
        </tr>
    </tbody>
</table>

</div>

<hr>

## Authors

- [@Aviaone](https://www.github.com/aviaone)

<br />
<br />

<div align="center">
<img align="top" src="https://komarev.com/ghpvc/?username=AviaOne&color=blueviolet"/>
</div>
