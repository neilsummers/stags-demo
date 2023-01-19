---
title: Strategy
layout: default
parent: Overall
nav_order: 3
---
# Target Selection
Stats to help track target selection. If the pin was in the center of the green, you aim at the pin, and your shot pattern is centered on your target, then you should miss the left/right of the pin in equal proportions.
When the pin is tucked close to the edge of the green then you should aim away from the pin to account for it being more difficult to get up and down from off the green, that it is on the green ... but by how much? If you have appropriate target selection, the number of shots it takes to get in from missing left/right of the pin should be the same regardless of how close the pin is to the edge of the green or to trouble. Since we track our targets relative to the hole location in the data, we can measure this to see how effective our target selection is. We can measure this 3 ways, using strokes gained, shots taken after your approach, or the number of shots you hit left/right of the hole/target.

{: .definition }
A tucked pin is defined as being a pin being less than `(distance/20)+2` from the edge of the green, where `distance` is the approach distance, and the edge of the green being the number of yards from the left/right edge if looking at left/right target selection, or front/back if looking at front/back target selection.

## Left/Right Relative to Hole
<table class="dataframe">
  <thead>
    <tr>
      <th>tucked</th>
      <th colspan="4" halign="left">all</th>
      <th colspan="4" halign="left">tucked</th>
      <th colspan="4" halign="left">not tucked</th>
    </tr>
    <tr>
      <th>pin</th>
      <th colspan="2" halign="left">left</th>
      <th colspan="2" halign="left">right</th>
      <th colspan="2" halign="left">left</th>
      <th colspan="2" halign="left">right</th>
      <th colspan="2" halign="left">left</th>
      <th colspan="2" halign="left">right</th>
    </tr>
    <tr>
      <th>target</th>
      <th>left</th>
      <th>right</th>
      <th>left</th>
      <th>right</th>
      <th>left</th>
      <th>right</th>
      <th>left</th>
      <th>right</th>
      <th>left</th>
      <th>right</th>
      <th>left</th>
      <th>right</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>SG</th>
      <td>-0.122759</td>
      <td>-0.075382</td>
      <td>-0.035607</td>
      <td>-0.345407</td>
      <td>-0.13504</td>
      <td>0.002593</td>
      <td>-0.104174</td>
      <td>-0.364154</td>
      <td>-0.046</td>
      <td>-0.376143</td>
      <td>0.2798</td>
      <td>0.142</td>
    </tr>
    <tr>
      <th>shots_after</th>
      <td>2.344828</td>
      <td>2.294118</td>
      <td>2.178571</td>
      <td>2.407407</td>
      <td>2.40000</td>
      <td>2.296296</td>
      <td>2.347826</td>
      <td>2.423077</td>
      <td>2.000</td>
      <td>2.285714</td>
      <td>1.4000</td>
      <td>2.000</td>
    </tr>
    <tr>
      <th>count</th>
      <td>29.000000</td>
      <td>34.000000</td>
      <td>28.000000</td>
      <td>27.000000</td>
      <td>25.00000</td>
      <td>27.000000</td>
      <td>23.000000</td>
      <td>26.000000</td>
      <td>4.000</td>
      <td>7.000000</td>
      <td>5.0000</td>
      <td>1.000</td>
    </tr>
  </tbody>
</table>

## Left/Right Target Selection
<table class="dataframe">
  <thead>
    <tr>
      <th>tucked</th>
      <th colspan="4" halign="left">all</th>
      <th colspan="4" halign="left">tucked</th>
      <th colspan="4" halign="left">not tucked</th>
    </tr>
    <tr>
      <th>pin</th>
      <th colspan="2" halign="left">left</th>
      <th colspan="2" halign="left">right</th>
      <th colspan="2" halign="left">left</th>
      <th colspan="2" halign="left">right</th>
      <th colspan="2" halign="left">left</th>
      <th colspan="2" halign="left">right</th>
    </tr>
    <tr>
      <th>target</th>
      <th>left</th>
      <th>right</th>
      <th>left</th>
      <th>right</th>
      <th>left</th>
      <th>right</th>
      <th>left</th>
      <th>right</th>
      <th>left</th>
      <th>right</th>
      <th>left</th>
      <th>right</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>SG</th>
      <td>-0.069455</td>
      <td>-0.162714</td>
      <td>-0.035607</td>
      <td>-0.332143</td>
      <td>-0.072690</td>
      <td>-0.091571</td>
      <td>-0.104174</td>
      <td>-0.349704</td>
      <td>-0.046</td>
      <td>-0.376143</td>
      <td>0.2798</td>
      <td>0.142</td>
    </tr>
    <tr>
      <th>shots_after</th>
      <td>2.272727</td>
      <td>2.392857</td>
      <td>2.178571</td>
      <td>2.392857</td>
      <td>2.310345</td>
      <td>2.428571</td>
      <td>2.347826</td>
      <td>2.407407</td>
      <td>2.000</td>
      <td>2.285714</td>
      <td>1.4000</td>
      <td>2.000</td>
    </tr>
    <tr>
      <th>count</th>
      <td>33.000000</td>
      <td>28.000000</td>
      <td>28.000000</td>
      <td>28.000000</td>
      <td>29.000000</td>
      <td>21.000000</td>
      <td>23.000000</td>
      <td>27.000000</td>
      <td>4.000</td>
      <td>7.000000</td>
      <td>5.0000</td>
      <td>1.000</td>
    </tr>
  </tbody>
</table>

## Long/Short Relative to Hole / Target
<table>
<tr>
<td>
Long/Short Relative to Hole
<table class="dataframe">
  <thead>
    <tr style="text-align: center;">
      <th></th>
      <th></th>
      <th></th>
      <th>SG</th>
      <th>shots_after</th>
      <th>count</th>
    </tr>
    <tr>
      <th>tucked</th>
      <th>pin</th>
      <th>target</th>
      <th></th>
      <th></th>
      <th></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th rowspan="4" valign="top">all</th>
      <th rowspan="2" valign="top">back</th>
      <th>long</th>
      <td>-0.088</td>
      <td>2.3</td>
      <td>22</td>
    </tr>
    <tr>
      <th>short</th>
      <td>-0.094</td>
      <td>2.2</td>
      <td>46</td>
    </tr>
    <tr>
      <th rowspan="2" valign="top">front</th>
      <th>long</th>
      <td>-0.008</td>
      <td>2.1</td>
      <td>34</td>
    </tr>
    <tr>
      <th>short</th>
      <td>-0.146</td>
      <td>2.3</td>
      <td>42</td>
    </tr>
    <tr>
      <th rowspan="4" valign="top">tucked</th>
      <th rowspan="2" valign="top">back</th>
      <th>long</th>
      <td>-0.116</td>
      <td>2.3</td>
      <td>12</td>
    </tr>
    <tr>
      <th>short</th>
      <td>-0.165</td>
      <td>2.4</td>
      <td>30</td>
    </tr>
    <tr>
      <th rowspan="2" valign="top">front</th>
      <th>long</th>
      <td>-0.093</td>
      <td>2.4</td>
      <td>17</td>
    </tr>
    <tr>
      <th>short</th>
      <td>-0.366</td>
      <td>2.3</td>
      <td>15</td>
    </tr>
    <tr>
      <th rowspan="4" valign="top">not tucked</th>
      <th rowspan="2" valign="top">back</th>
      <th>long</th>
      <td>-0.053</td>
      <td>2.3</td>
      <td>10</td>
    </tr>
    <tr>
      <th>short</th>
      <td>0.038</td>
      <td>1.9</td>
      <td>16</td>
    </tr>
    <tr>
      <th rowspan="2" valign="top">front</th>
      <th>long</th>
      <td>0.078</td>
      <td>1.9</td>
      <td>17</td>
    </tr>
    <tr>
      <th>short</th>
      <td>-0.023</td>
      <td>2.3</td>
      <td>27</td>
    </tr>
  </tbody>
</table>
</td>
<td>
Long/Short Target Selection 
<table class="dataframe">
  <thead>
    <tr style="text-align: center;">
      <th></th>
      <th></th>
      <th></th>
      <th>SG</th>
      <th>shots_after</th>
      <th>count</th>
    </tr>
    <tr>
      <th>tucked</th>
      <th>pin</th>
      <th>target</th>
      <th></th>
      <th></th>
      <th></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th rowspan="4" valign="top">all</th>
      <th rowspan="2" valign="top">back</th>
      <th>long</th>
      <td>-0.126</td>
      <td>2.4</td>
      <td>20</td>
    </tr>
    <tr>
      <th>short</th>
      <td>-0.090</td>
      <td>2.2</td>
      <td>47</td>
    </tr>
    <tr>
      <th rowspan="2" valign="top">front</th>
      <th>long</th>
      <td>-0.015</td>
      <td>2.2</td>
      <td>33</td>
    </tr>
    <tr>
      <th>short</th>
      <td>-0.146</td>
      <td>2.3</td>
      <td>42</td>
    </tr>
    <tr>
      <th rowspan="4" valign="top">tucked</th>
      <th rowspan="2" valign="top">back</th>
      <th>long</th>
      <td>-0.199</td>
      <td>2.4</td>
      <td>10</td>
    </tr>
    <tr>
      <th>short</th>
      <td>-0.156</td>
      <td>2.4</td>
      <td>31</td>
    </tr>
    <tr>
      <th rowspan="2" valign="top">front</th>
      <th>long</th>
      <td>-0.093</td>
      <td>2.4</td>
      <td>17</td>
    </tr>
    <tr>
      <th>short</th>
      <td>-0.366</td>
      <td>2.3</td>
      <td>15</td>
    </tr>
    <tr>
      <th rowspan="4" valign="top">not tucked</th>
      <th rowspan="2" valign="top">back</th>
      <th>long</th>
      <td>-0.053</td>
      <td>2.3</td>
      <td>10</td>
    </tr>
    <tr>
      <th>short</th>
      <td>0.038</td>
      <td>1.9</td>
      <td>16</td>
    </tr>
    <tr>
      <th rowspan="2" valign="top">front</th>
      <th>long</th>
      <td>0.067</td>
      <td>1.9</td>
      <td>16</td>
    </tr>
    <tr>
      <th>short</th>
      <td>-0.023</td>
      <td>2.3</td>
      <td>27</td>
    </tr>
  </tbody>
</table>
</td>
</tr>
</table>
