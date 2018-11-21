---
title: jQuery选择器总结
date: Invalid date
tags:
  - 未分类
translate_title: jquery-selector-summary
---

<table border="0" cellspacing="0" cellpadding="0">
<tbody>
<tr>
<td class="gutter">
<div class="line number1 index0 alt2">1</div>
<div class="line number2 index1 alt1">2</div>
<div class="line number3 index2 alt2">3</div>
<div class="line number4 index3 alt1">4</div>
<div class="line number5 index4 alt2">5</div>
<div class="line number6 index5 alt1">6</div>
<div class="line number7 index6 alt2">7</div>
<div class="line number8 index7 alt1">8</div>
<div class="line number9 index8 alt2">9</div>
<div class="line number10 index9 alt1">10</div>
<div class="line number11 index10 alt2">11</div>
<div class="line number12 index11 alt1">12</div>
<div class="line number13 index12 alt2">13</div>
<div class="line number14 index13 alt1">14</div>
<div class="line number15 index14 alt2">15</div>
<div class="line number16 index15 alt1">16</div>
<div class="line number17 index16 alt2">17</div>
<div class="line number18 index17 alt1">18</div>
<div class="line number19 index18 alt2">19</div>
<div class="line number20 index19 alt1">20</div>
<div class="line number21 index20 alt2">21</div>
<div class="line number22 index21 alt1">22</div>
<div class="line number23 index22 alt2">23</div>
<div class="line number24 index23 alt1">24</div>
<div class="line number25 index24 alt2">25</div>
<div class="line number26 index25 alt1">26</div>
<div class="line number27 index26 alt2">27</div>
<div class="line number28 index27 alt1">28</div>
<div class="line number29 index28 alt2">29</div>
<div class="line number30 index29 alt1">30</div>
<div class="line number31 index30 alt2">31</div>
<div class="line number32 index31 alt1">32</div>
<div class="line number33 index32 alt2">33</div>
<div class="line number34 index33 alt1">34</div>
<div class="line number35 index34 alt2">35</div>
<div class="line number36 index35 alt1">36</div>
<div class="line number37 index36 alt2">37</div>
<div class="line number38 index37 alt1">38</div>
<div class="line number39 index38 alt2">39</div>
<div class="line number40 index39 alt1">40</div>
<div class="line number41 index40 alt2">41</div>
<div class="line number42 index41 alt1">42</div>
<div class="line number43 index42 alt2">43</div>
<div class="line number44 index43 alt1">44</div>
<div class="line number45 index44 alt2">45</div>
<div class="line number46 index45 alt1">46</div>
<div class="line number47 index46 alt2">47</div>
<div class="line number48 index47 alt1">48</div>
<div class="line number49 index48 alt2">49</div>
<div class="line number50 index49 alt1">50</div>
<div class="line number51 index50 alt2">51</div>
<div class="line number52 index51 alt1">52</div>
<div class="line number53 index52 alt2">53</div>
<div class="line number54 index53 alt1">54</div>
<div class="line number55 index54 alt2">55</div>
<div class="line number56 index55 alt1">56</div>
<div class="line number57 index56 alt2">57</div>
<div class="line number58 index57 alt1">58</div>
<div class="line number59 index58 alt2">59</div>
<div class="line number60 index59 alt1">60</div>
<div class="line number61 index60 alt2">61</div>
<div class="line number62 index61 alt1">62</div>
<div class="line number63 index62 alt2">63</div>
<div class="line number64 index63 alt1">64</div>
<div class="line number65 index64 alt2">65</div>
<div class="line number66 index65 alt1">66</div>
<div class="line number67 index66 alt2">67</div>
<div class="line number68 index67 alt1">68</div>
<div class="line number69 index68 alt2">69</div>
<div class="line number70 index69 alt1">70</div>
<div class="line number71 index70 alt2">71</div>
<div class="line number72 index71 alt1">72</div>
<div class="line number73 index72 alt2">73</div>
<div class="line number74 index73 alt1">74</div>
<div class="line number75 index74 alt2">75</div>
<div class="line number76 index75 alt1">76</div>
<div class="line number77 index76 alt2">77</div>
<div class="line number78 index77 alt1">78</div>
<div class="line number79 index78 alt2">79</div>
<div class="line number80 index79 alt1">80</div>
<div class="line number81 index80 alt2">81</div>
<div class="line number82 index81 alt1">82</div>
<div class="line number83 index82 alt2">83</div>
<div class="line number84 index83 alt1">84</div>
<div class="line number85 index84 alt2">85</div>
<div class="line number86 index85 alt1">86</div>
<div class="line number87 index86 alt2">87</div>
<div class="line number88 index87 alt1">88</div>
<div class="line number89 index88 alt2">89</div>
<div class="line number90 index89 alt1">90</div>
<div class="line number91 index90 alt2">91</div>
<div class="line number92 index91 alt1">92</div>
<div class="line number93 index92 alt2">93</div>
<div class="line number94 index93 alt1">94</div>
<div class="line number95 index94 alt2">95</div>
<div class="line number96 index95 alt1">96</div>
<div class="line number97 index96 alt2">97</div>
<div class="line number98 index97 alt1">98</div>
<div class="line number99 index98 alt2">99</div>
<div class="line number100 index99 alt1">100</div>
<div class="line number101 index100 alt2">101</div>
<div class="line number102 index101 alt1">102</div>
<div class="line number103 index102 alt2">103</div>
<div class="line number104 index103 alt1">104</div>
<div class="line number105 index104 alt2">105</div>
<div class="line number106 index105 alt1">106</div>
<div class="line number107 index106 alt2">107</div>
<div class="line number108 index107 alt1">108</div>
<div class="line number109 index108 alt2">109</div>
<div class="line number110 index109 alt1">110</div>
<div class="line number111 index110 alt2">111</div>
<div class="line number112 index111 alt1">112</div>
<div class="line number113 index112 alt2">113</div>
<div class="line number114 index113 alt1">114</div>
<div class="line number115 index114 alt2">115</div>
<div class="line number116 index115 alt1">116</div>
<div class="line number117 index116 alt2">117</div>
<div class="line number118 index117 alt1">118</div>
<div class="line number119 index118 alt2">119</div>
<div class="line number120 index119 alt1">120</div>
<div class="line number121 index120 alt2">121</div>
<div class="line number122 index121 alt1">122</div>
<div class="line number123 index122 alt2">123</div>
<div class="line number124 index123 alt1">124</div>
<div class="line number125 index124 alt2">125</div>
<div class="line number126 index125 alt1">126</div>
<div class="line number127 index126 alt2">127</div>
<div class="line number128 index127 alt1">128</div>
<div class="line number129 index128 alt2">129</div>
<div class="line number130 index129 alt1">130</div>
<div class="line number131 index130 alt2">131</div>
<div class="line number132 index131 alt1">132</div>
<div class="line number133 index132 alt2">133</div>
<div class="line number134 index133 alt1">134</div>
<div class="line number135 index134 alt2">135</div>
<div class="line number136 index135 alt1">136</div>
<div class="line number137 index136 alt2">137</div>
<div class="line number138 index137 alt1">138</div>
<div class="line number139 index138 alt2">139</div>
<div class="line number140 index139 alt1">140</div>
<div class="line number141 index140 alt2">141</div>
<div class="line number142 index141 alt1">142</div>
<div class="line number143 index142 alt2">143</div>
<div class="line number144 index143 alt1">144</div>
<div class="line number145 index144 alt2">145</div>
<div class="line number146 index145 alt1">146</div>
<div class="line number147 index146 alt2">147</div>
<div class="line number148 index147 alt1">148</div>
<div class="line number149 index148 alt2">149</div>
<div class="line number150 index149 alt1">150</div>
<div class="line number151 index150 alt2">151</div>
<div class="line number152 index151 alt1">152</div>
<div class="line number153 index152 alt2">153</div>
<div class="line number154 index153 alt1">154</div>
<div class="line number155 index154 alt2">155</div>
<div class="line number156 index155 alt1">156</div>
<div class="line number157 index156 alt2">157</div>
<div class="line number158 index157 alt1">158</div>
<div class="line number159 index158 alt2">159</div>
<div class="line number160 index159 alt1">160</div>
<div class="line number161 index160 alt2">161</div>
<div class="line number162 index161 alt1">162</div>
<div class="line number163 index162 alt2">163</div>
<div class="line number164 index163 alt1">164</div>
<div class="line number165 index164 alt2">165</div>
<div class="line number166 index165 alt1">166</div>
<div class="line number167 index166 alt2">167</div>
<div class="line number168 index167 alt1">168</div>
<div class="line number169 index168 alt2">169</div>
<div class="line number170 index169 alt1">170</div>
<div class="line number171 index170 alt2">171</div>
<div class="line number172 index171 alt1">172</div>
<div class="line number173 index172 alt2">173</div>
<div class="line number174 index173 alt1">174</div>
<div class="line number175 index174 alt2">175</div>
<div class="line number176 index175 alt1">176</div>
<div class="line number177 index176 alt2">177</div>
<div class="line number178 index177 alt1">178</div>
<div class="line number179 index178 alt2">179</div>
<div class="line number180 index179 alt1">180</div>
<div class="line number181 index180 alt2">181</div>
<div class="line number182 index181 alt1">182</div>
<div class="line number183 index182 alt2">183</div>
<div class="line number184 index183 alt1">184</div>
<div class="line number185 index184 alt2">185</div>
<div class="line number186 index185 alt1">186</div></td>
<td class="code">
<div class="container">
<div class="line number1 index0 alt2">`jQuery 的选择器可谓之强大无比，这里简单地总结一下常用的元素查找方法 `</div>
<div class="line number2 index1 alt1"></div>
<div class="line number3 index2 alt2">`$(``"#myELement"``)    选择id值等于myElement的元素，id值不能重复在文档中只能有一个id值是myElement所以得到的是唯一的元素 `</div>
<div class="line number4 index3 alt1">`$(``"div"``)           选择所有的div标签元素，返回div元素数组 `</div>
<div class="line number5 index4 alt2">`$(``".myClass"``)      选择使用myClass类的css的所有元素 `</div>
<div class="line number6 index5 alt1">`$(``"*"``)             选择文档中的所有的元素，可以运用多种的选择方式进行联合选择：例如$(``"#myELement,div,.myclass"``) `</div>
<div class="line number7 index6 alt2"></div>
<div class="line number8 index7 alt1">`层叠选择器： `</div>
<div class="line number9 index8 alt2">`$(``"form input"``)         选择所有的form元素中的input元素 `</div>
<div class="line number10 index9 alt1">`$(``"#main &gt; *"``)          选择id值为main的所有的子元素 `</div>
<div class="line number11 index10 alt2">`$(``"label + input"``)     选择所有的label元素的下一个input元素节点，经测试选择器返回的是label标签后面直接跟一个input标签的所有input标签元素 `</div>
<div class="line number12 index11 alt1">`$(``"#prev ~ div"``)       同胞选择器，该选择器返回的为id为prev的标签元素的所有的属于同一个父元素的div标签 `</div>
<div class="line number13 index12 alt2"></div>
<div class="line number14 index13 alt1">`基本过滤选择器： `</div>
<div class="line number15 index14 alt2">`$(``"tr:first"``)               选择所有tr元素的第一个 `</div>
<div class="line number16 index15 alt1">`$(``"tr:last"``)                选择所有tr元素的最后一个 `</div>
<div class="line number17 index16 alt2">`$(``"input:not(:checked) + span"``)   `</div>
<div class="line number18 index17 alt1"></div>
<div class="line number19 index18 alt2">`过滤掉：checked的选择器的所有的input元素 `</div>
<div class="line number20 index19 alt1"></div>
<div class="line number21 index20 alt2">`$(``"tr:even"``)               选择所有的tr元素的第0，2，4... ...个元素（注意：因为所选择的多个元素时为数组，所以序号是从0开始） `</div>
<div class="line number22 index21 alt1"></div>
<div class="line number23 index22 alt2">`$(``"tr:odd"``)                选择所有的tr元素的第1，3，5... ...个元素 `</div>
<div class="line number24 index23 alt1">`$(``"td:eq(2)"``)             选择所有的td元素中序号为2的那个td元素 `</div>
<div class="line number25 index24 alt2">`$(``"td:gt(4)"``)             选择td元素中序号大于4的所有td元素 `</div>
<div class="line number26 index25 alt1">`$(``"td:ll(4)"``)              选择td元素中序号小于4的所有的td元素 `</div>
<div class="line number27 index26 alt2">`$(``":header"``) `</div>
<div class="line number28 index27 alt1">`$(``"div:animated"``) `</div>
<div class="line number29 index28 alt2">`内容过滤选择器： `</div>
<div class="line number30 index29 alt1"></div>
<div class="line number31 index30 alt2">`$(``"div:contains('John')"``) 选择所有div中含有John文本的元素 `</div>
<div class="line number32 index31 alt1">`$(``"td:empty"``)           选择所有的为空（也不包括文本节点）的td元素的数组 `</div>
<div class="line number33 index32 alt2">`$(``"div:has(p)"``)        选择所有含有p标签的div元素 `</div>
<div class="line number34 index33 alt1">`$(``"td:parent"``)          选择所有的以td为父节点的元素数组 `</div>
<div class="line number35 index34 alt2">`可视化过滤选择器： `</div>
<div class="line number36 index35 alt1"></div>
<div class="line number37 index36 alt2">`$(``"div:hidden"``)        选择所有的被hidden的div元素 `</div>
<div class="line number38 index37 alt1">`$(``"div:visible"``)        选择所有的可视化的div元素 `</div>
<div class="line number39 index38 alt2">`属性过滤选择器： `</div>
<div class="line number40 index39 alt1"></div>
<div class="line number41 index40 alt2">`$(``"div[id]"``)              选择所有含有id属性的div元素 `</div>
<div class="line number42 index41 alt1">`$(``"input[name='newsletter']"``)    选择所有的name属性等于``'newsletter'``的input元素 `</div>
<div class="line number43 index42 alt2"></div>
<div class="line number44 index43 alt1">`$(``"input[name!='newsletter']"``) 选择所有的name属性不等于``'newsletter'``的input元素 `</div>
<div class="line number45 index44 alt2"></div>
<div class="line number46 index45 alt1">`$(``"input[name^='news']"``)         选择所有的name属性以``'news'``开头的input元素 `</div>
<div class="line number47 index46 alt2">`$(``"input[name$='news']"``)         选择所有的name属性以``'news'``结尾的input元素 `</div>
<div class="line number48 index47 alt1">`$(``"input[name*='man']"``)          选择所有的name属性包含``'news'``的input元素 `</div>
<div class="line number49 index48 alt2"></div>
<div class="line number50 index49 alt1">`$(``"input[id][name$='man']"``)    可以使用多个属性进行联合选择，该选择器是得到所有的含有id属性并且那么属性以man结尾的元素 `</div>
<div class="line number51 index50 alt2"></div>
<div class="line number52 index51 alt1">`子元素过滤选择器： `</div>
<div class="line number53 index52 alt2"></div>
<div class="line number54 index53 alt1">`$(``"ul li:nth-child(2)"``),$(``"ul li:nth-child(odd)"``),$(``"ul li:nth-child(3n + 1)"``) `</div>
<div class="line number55 index54 alt2"></div>
<div class="line number56 index55 alt1">`$(``"div span:first-child"``)          返回所有的div元素的第一个子节点的数组 `</div>
<div class="line number57 index56 alt2">`$(``"div span:last-child"``)           返回所有的div元素的最后一个节点的数组 `</div>
<div class="line number58 index57 alt1">`$(``"div button:only-child"``)       返回所有的div中只有唯一一个子节点的所有子节点的数组 `</div>
<div class="line number59 index58 alt2"></div>
<div class="line number60 index59 alt1">`表单元素选择器： `</div>
<div class="line number61 index60 alt2"></div>
<div class="line number62 index61 alt1">`$(``":input"``)                  选择所有的表单输入元素，包括input, textarea, select 和 button `</div>
<div class="line number63 index62 alt2"></div>
<div class="line number64 index63 alt1">`$(``":text"``)                     选择所有的text input元素 `</div>
<div class="line number65 index64 alt2">`$(``":password"``)           选择所有的password input元素 `</div>
<div class="line number66 index65 alt1">`$(``":radio"``)                   选择所有的radio input元素 `</div>
<div class="line number67 index66 alt2">`$(``":checkbox"``)            选择所有的checkbox input元素 `</div>
<div class="line number68 index67 alt1">`$(``":submit"``)               选择所有的submit input元素 `</div>
<div class="line number69 index68 alt2">`$(``":image"``)                 选择所有的image input元素 `</div>
<div class="line number70 index69 alt1">`$(``":reset"``)                   选择所有的reset input元素 `</div>
<div class="line number71 index70 alt2">`$(``":button"``)                选择所有的button input元素 `</div>
<div class="line number72 index71 alt1">`$(``":file"``)                     选择所有的file input元素 `</div>
<div class="line number73 index72 alt2">`$(``":hidden"``)               选择所有类型为hidden的input元素或表单的隐藏域 `</div>
<div class="line number74 index73 alt1"></div>
<div class="line number75 index74 alt2">`表单元素过滤选择器： `</div>
<div class="line number76 index75 alt1"></div>
<div class="line number77 index76 alt2">`$(``":enabled"``)             选择所有的可操作的表单元素 `</div>
<div class="line number78 index77 alt1">`$(``":disabled"``)            选择所有的不可操作的表单元素 `</div>
<div class="line number79 index78 alt2">`$(``":checked"``)            选择所有的被checked的表单元素 `</div>
<div class="line number80 index79 alt1">`$(``"select option:selected"``) 选择所有的select 的子元素中被selected的元素 `</div>
<div class="line number81 index80 alt2"></div>
<div class="line number82 index81 alt1">` `</div>
<div class="line number83 index82 alt2"></div>
<div class="line number84 index83 alt1">`选取一个 name 为”S_03_22″的input text框的上一个td的text值`</div>
<div class="line number85 index84 alt2">`$(”input[@ name =S_03_22]“).parent().prev().text() `</div>
<div class="line number86 index85 alt1"></div>
<div class="line number87 index86 alt2">`名字以”S_”开始，并且不是以”_R”结尾的`</div>
<div class="line number88 index87 alt1">`$(”input[@ name ^=``'S_'``]“).not(”[@ name $=``'_R'``]“) `</div>
<div class="line number89 index88 alt2"></div>
<div class="line number90 index89 alt1">`一个名为 radio_01的radio所选的值`</div>
<div class="line number91 index90 alt2">`$(”input[@ name =radio_01][@checked]“).val(); `</div>
<div class="line number92 index91 alt1"></div>
<div class="line number93 index92 alt2">` `</div>
<div class="line number94 index93 alt1"></div>
<div class="line number95 index94 alt2">` `</div>
<div class="line number96 index95 alt1"></div>
<div class="line number97 index96 alt2">`$(``"A B"``) 查找A元素下面的所有子节点，包括非直接子节点`</div>
<div class="line number98 index97 alt1">`$(``"A&gt;B"``) 查找A元素下面的直接子节点`</div>
<div class="line number99 index98 alt2">`$(``"A+B"``) 查找A元素后面的兄弟节点，包括非直接子节点`</div>
<div class="line number100 index99 alt1">`$(``"A~B"``) 查找A元素后面的兄弟节点，不包括非直接子节点 `</div>
<div class="line number101 index100 alt2"></div>
<div class="line number102 index101 alt1">`1\. $(``"A B"``) 查找A元素下面的所有子节点，包括非直接子节点 `</div>
<div class="line number103 index102 alt2"></div>
<div class="line number104 index103 alt1">`例子：找到表单中所有的 input 元素 `</div>
<div class="line number105 index104 alt2"></div>
<div class="line number106 index105 alt1">`HTML 代码: `</div>
<div class="line number107 index106 alt2"></div>
<div class="line number108 index107 alt1">`&lt;form&gt;`</div>
<div class="line number109 index108 alt2">`&lt;label&gt;Name:&lt;/label&gt;`</div>
<div class="line number110 index109 alt1">`&lt;input name=``"name"` `/&gt;`</div>
<div class="line number111 index110 alt2">`&lt;fieldset&gt;`</div>
<div class="line number112 index111 alt1">`      ``&lt;label&gt;Newsletter:&lt;/label&gt;`</div>
<div class="line number113 index112 alt2">`      ``&lt;input name=``"newsletter"` `/&gt;`</div>
<div class="line number114 index113 alt1">`&lt;/fieldset&gt;`</div>
<div class="line number115 index114 alt2">`&lt;/form&gt;`</div>
<div class="line number116 index115 alt1">`&lt;input name=``"none"` `/&gt; `</div>
<div class="line number117 index116 alt2">`jQuery 代码: `</div>
<div class="line number118 index117 alt1"></div>
<div class="line number119 index118 alt2">`$(``"form input"``) `</div>
<div class="line number120 index119 alt1">`结果: `</div>
<div class="line number121 index120 alt2"></div>
<div class="line number122 index121 alt1">`[ &lt;input name=``"name"` `/&gt;, &lt;input name=``"newsletter"` `/&gt; ] `</div>
<div class="line number123 index122 alt2"></div>
<div class="line number124 index123 alt1">`2\. $(``"A&gt;B"``) 查找A元素下面的直接子节点 `</div>
<div class="line number125 index124 alt2">`例子：匹配表单中所有的子级input元素。 `</div>
<div class="line number126 index125 alt1"></div>
<div class="line number127 index126 alt2">`HTML 代码: `</div>
<div class="line number128 index127 alt1"></div>
<div class="line number129 index128 alt2">`&lt;form&gt;`</div>
<div class="line number130 index129 alt1">`&lt;label&gt;Name:&lt;/label&gt;`</div>
<div class="line number131 index130 alt2">`&lt;input name=``"name"` `/&gt;`</div>
<div class="line number132 index131 alt1">`&lt;fieldset&gt;`</div>
<div class="line number133 index132 alt2">`      ``&lt;label&gt;Newsletter:&lt;/label&gt;`</div>
<div class="line number134 index133 alt1">`      ``&lt;input name=``"newsletter"` `/&gt;`</div>
<div class="line number135 index134 alt2">`&lt;/fieldset&gt;`</div>
<div class="line number136 index135 alt1">`&lt;/form&gt;`</div>
<div class="line number137 index136 alt2">`&lt;input name=``"none"` `/&gt; `</div>
<div class="line number138 index137 alt1">`jQuery 代码: `</div>
<div class="line number139 index138 alt2"></div>
<div class="line number140 index139 alt1">`$(``"form &gt; input"``) `</div>
<div class="line number141 index140 alt2">`结果: `</div>
<div class="line number142 index141 alt1"></div>
<div class="line number143 index142 alt2">`[ &lt;input name=``"name"` `/&gt; ] `</div>
<div class="line number144 index143 alt1"></div>
<div class="line number145 index144 alt2">`3\. $(``"A+B"``) 查找A元素后面的兄弟节点，包括非直接子节点 `</div>
<div class="line number146 index145 alt1">`例子：匹配所有跟在 label 后面的 input 元素 `</div>
<div class="line number147 index146 alt2"></div>
<div class="line number148 index147 alt1">`HTML 代码: `</div>
<div class="line number149 index148 alt2"></div>
<div class="line number150 index149 alt1">`&lt;form&gt;`</div>
<div class="line number151 index150 alt2">`&lt;label&gt;Name:&lt;/label&gt;`</div>
<div class="line number152 index151 alt1">`&lt;input name=``"name"` `/&gt;`</div>
<div class="line number153 index152 alt2">`&lt;fieldset&gt;`</div>
<div class="line number154 index153 alt1">`      ``&lt;label&gt;Newsletter:&lt;/label&gt;`</div>
<div class="line number155 index154 alt2">`      ``&lt;input name=``"newsletter"` `/&gt;`</div>
<div class="line number156 index155 alt1">`&lt;/fieldset&gt;`</div>
<div class="line number157 index156 alt2">`&lt;/form&gt;`</div>
<div class="line number158 index157 alt1">`&lt;input name=``"none"` `/&gt; `</div>
<div class="line number159 index158 alt2">`jQuery 代码: `</div>
<div class="line number160 index159 alt1"></div>
<div class="line number161 index160 alt2">`$(``"label + input"``) `</div>
<div class="line number162 index161 alt1">`结果: `</div>
<div class="line number163 index162 alt2"></div>
<div class="line number164 index163 alt1">`[ &lt;input name=``"name"` `/&gt;, &lt;input name=``"newsletter"` `/&gt; ] `</div>
<div class="line number165 index164 alt2"></div>
<div class="line number166 index165 alt1"></div>
<div class="line number167 index166 alt2">`4\. $(``"A~B"``) 查找A元素后面的兄弟节点，不包括非直接子节点 `</div>
<div class="line number168 index167 alt1">`例子：找到所有与表单同辈的 input 元素 `</div>
<div class="line number169 index168 alt2"></div>
<div class="line number170 index169 alt1">`HTML 代码: `</div>
<div class="line number171 index170 alt2"></div>
<div class="line number172 index171 alt1">`&lt;form&gt;`</div>
<div class="line number173 index172 alt2">`&lt;label&gt;Name:&lt;/label&gt;`</div>
<div class="line number174 index173 alt1">`&lt;input name=``"name"` `/&gt;`</div>
<div class="line number175 index174 alt2">`&lt;fieldset&gt;`</div>
<div class="line number176 index175 alt1">`      ``&lt;label&gt;Newsletter:&lt;/label&gt;`</div>
<div class="line number177 index176 alt2">`      ``&lt;input name=``"newsletter"` `/&gt;`</div>
<div class="line number178 index177 alt1">`&lt;/fieldset&gt;`</div>
<div class="line number179 index178 alt2">`&lt;/form&gt;`</div>
<div class="line number180 index179 alt1">`&lt;input name=``"none"` `/&gt; `</div>
<div class="line number181 index180 alt2">`jQuery 代码: `</div>
<div class="line number182 index181 alt1"></div>
<div class="line number183 index182 alt2">`$(``"form ~ input"``) `</div>
<div class="line number184 index183 alt1">`结果: `</div>
<div class="line number185 index184 alt2"></div>
<div class="line number186 index185 alt1">`[ &lt;input name=``"none"` `/&gt; ] `</div>
</div></td>
</tr>
</tbody>
</table>