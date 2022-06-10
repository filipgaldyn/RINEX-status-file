# RINEX-status-file
<h2>Software to generate a status file based on RINEX v3 from IGS MGEX stations</h2><br>
<li>main file to run script: main.py </li>
<li>dataset uses in software: data_to_script (MGEX list, satellite list) </li>
<li>folder to generated status files: download_data</li>
<li>bnc.exe.lnk <a href="https://igs.bkg.bund.de/ntrip/bnc">BKG Ntrip Client (BNC)</a></li>
<li>crx2rnx.exe <a href="https://terras.gsi.go.jp/ja/crx2rnx.html">RNXCMP software</a></li>
<li>gfzrnx_1.15.exe <a href="https://dataservices.gfz-potsdam.de/panmetaworks/showshort.php?id=escidoc:1577894">GFZRNX</a></li>
<h3>Processing diagram</h3><br>
<img src="download_scheme.png" alt="download_scheme" width="400" height="500"><br>
<h4>Software export csv files with: files:</h4>
<li>daily satellite report for each PRN per day</li>
<li>daily quality report for individual signal per day</li>
