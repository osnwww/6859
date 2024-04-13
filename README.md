# 6859

<!--------#### Table 1： Statistics of Datasets-------->
<h4 align = "center">Table1:  Statistics of datasets</h4>
<table align = "center">
    <tr>
        <th align="left">Datasets</th>
        <th># graph  </th>
        <th># class </th>
        <th>avg.# V</th>
        <th>avg.# E </th>
        <th>anomaly(%)</th>
    </tr>
    <tr>
        <td>AIDS</td>
        <td align="center">2000</td>
        <td align="center">2</td>
        <td align="center">15.62</td>
        <td align="center">32.50</td>
        <td align="center">2.4%</td>
    </tr>
    <tr>
        <td>PROTEINS</td>
        <td align="center">1113</td>
        <td align="center">2</td>
        <td align="center">40.00</td>
        <td align="center">145.65</td>
        <td align="center">12.7%</td>
    </tr>
</table>

<!-----------#### Table2: **********************************--------->
<h4 align = "center">Table2: Performance comparison between MotifCAR and baselines on two datasets.</h4>
<table align = "center">
    <tr>
        <th align="left" rowspan="2" >Method</th>
        <th colspan="3" >AIDS</th>
        <th colspan="3">PROTEINS</th>
    </tr>
    <tr>
        <th>PRE</th>
        <th>RECALL</th>
        <th>F1</th>
        <th>PRE</th>
        <th>RECALL</th>
        <th>F1</td>
    </tr>
    <tr>
        <td nowrap="nowrap">g-U-Nets</td>
        <td nowrap="nowrap">0.85±0.12</td>
        <td nowrap="nowrap">0.83±0.23</td>
        <td nowrap="nowrap">0.84±0.31</td>
        <td nowrap="nowrap">0.81±0.07</td>
        <td nowrap="nowrap">0.79±0.22</td>
        <td nowrap="nowrap">0.78±0.06</td>
    </tr>
    <tr>
        <td nowrap="nowrap">DiffPool</td>
        <td nowrap="nowrap">0.69±0.23</td>
        <td nowrap="nowrap">0.72±0.21</td>
        <td nowrap="nowrap">0.70±0.12</td>
        <td nowrap="nowrap">0.76±0.15</td>
        <td nowrap="nowrap">0.66±0.21</td>
        <td nowrap="nowrap">0.71±0.11</td>
    </tr>
    <tr>
        <td nowrap="nowrap">SAGPool</td>
        <td nowrap="nowrap">0.81±0.06</td>
        <td nowrap="nowrap">0.84±0.14</td>
        <td nowrap="nowrap">0.85±0.15</td>
        <td nowrap="nowrap">0.81±0.13</td>
        <td nowrap="nowrap">0.80±0.08</td>
        <td nowrap="nowrap">0.73±0.23</td>
    </tr>
    <tr>
        <td nowrap="nowrap">GMT</td>
        <td nowrap="nowrap">0.83±0.13</td>
        <td nowrap="nowrap">0.87±0.11</td>
        <td nowrap="nowrap">0.87±0.12</td>
        <td nowrap="nowrap">0.85±0.07</td>
        <td nowrap="nowrap">0.83±0.08</td>
        <td nowrap="nowrap">0.80±0.09</td>
    </tr>
    <tr>
        <td nowrap="nowrap">CFGL-LCR</td>
        <td nowrap="nowrap">0.84±0.14</td>
        <td nowrap="nowrap">0.88±0.12</td>
        <td nowrap="nowrap">0.85±0.21</td>
        <td nowrap="nowrap">0.84±0.22</td>
        <td nowrap="nowrap">0.88±0.15</td>
        <td nowrap="nowrap">0.86±0.09</td>
    </tr>
    <tr>
        <td nowrap="nowrap">CFAD</td>
        <td nowrap="nowrap">0.87±0.13</td>
        <td nowrap="nowrap">0.90±0.10</td>
        <td nowrap="nowrap">0.85±0.15</td>
        <td nowrap="nowrap">0.91±0.13</td>
        <td nowrap="nowrap">0.94±0.06</td>
        <td nowrap="nowrap">0.88±0.13</td>
    </tr>
    <tr>
        <td nowrap="nowrap">CGC</td>
        <td nowrap="nowrap">0.90±0.12</td>
        <td nowrap="nowrap">0.92±0.11</td>
        <td nowrap="nowrap">0.86±0.12</td>
        <td nowrap="nowrap">0.88±0.13</td>
        <td nowrap="nowrap">0.92±0.12</td>
        <td nowrap="nowrap">0.88±0.16</td>
    </tr>
    <tr>
        <td nowrap="nowrap">CF-HGExp</td>
        <td nowrap="nowrap">0.92±0.13</td>
        <td nowrap="nowrap">0.96±0.12</td>
        <td nowrap="nowrap">0.94±0.11</td>
        <td nowrap="nowrap">0.86±0.12</td>
        <td nowrap="nowrap">0.91±0.13</td>
        <td nowrap="nowrap">0.89±0.11</td>
    </tr>
    <tr>
        <td nowrap="nowrap">OCGTL</td>
        <td nowrap="nowrap">0.88±0.08</td>
        <td nowrap="nowrap">0.85±0.11</td>
        <td nowrap="nowrap">0.84±0.12</td>
        <td nowrap="nowrap">0.88±0.08</td>
        <td nowrap="nowrap">0.82±0.03</td>
        <td nowrap="nowrap">0.84±0.08</td>
    </tr>
    <tr>
        <td nowrap="nowrap">GLocalKD</td>
        <td nowrap="nowrap">0.67±0.23</td>
        <td nowrap="nowrap">0.63±0.15</td>
        <td nowrap="nowrap">0.62±0.28</td>
        <td nowrap="nowrap">0.66±0.15</td>
        <td nowrap="nowrap">0.63±0.13</td>
        <td nowrap="nowrap">0.64±0.22</td>
    </tr>
    <tr>
        <td nowrap="nowrap">iGAD</td>
        <td nowrap="nowrap">0.78±0.26</td>
        <td nowrap="nowrap">0.87±0.23</td>
        <td nowrap="nowrap">0.76±0.16</td>
        <td nowrap="nowrap">0.89±0.25</td>
        <td nowrap="nowrap">0.83±0.13</td>
        <td nowrap="nowrap">0.81±0.23</td>
    </tr>
    <tr>
        <td nowrap="nowrap">GmapAD</td>
        <td nowrap="nowrap">0.94±0.13</td>
        <td nowrap="nowrap">0.97±0.05</td>
        <td nowrap="nowrap">0.97±0.08</td>
        <td nowrap="nowrap">0.87±0.05</td>
        <td nowrap="nowrap">0.95±0.03</td>
        <td nowrap="nowrap">0.92±0.12</td>
    </tr>
    <tr>
        <td nowrap="nowrap">MotifCAR</td>
        <td nowrap="nowrap">0.96±0.03</td>
        <td nowrap="nowrap">0.98±0.02</td>
        <td nowrap="nowrap">0.99±0.06</td>
        <td nowrap="nowrap">0.91±0.09</td>
        <td nowrap="nowrap">0.97±0.06</td>
        <td nowrap="nowrap">0.94±0.06</td>
    </tr>
</table>

