<html>
<head>
<title>LaTeX4Web 1.4 OUTPUT</title>
<style type="text/css">
<!--
 body {color: black;  background:"#FFCC99";  }
 div.p { margin-top: 7pt;}
 td div.comp { margin-top: -0.6ex; margin-bottom: -1ex;}
 td div.comb { margin-top: -0.6ex; margin-bottom: -.6ex;}
 td div.norm {line-height:normal;}
 td div.hrcomp { line-height: 0.9; margin-top: -0.8ex; margin-bottom: -1ex;}
 td.sqrt {border-top:2 solid black;
          border-left:2 solid black;
          border-bottom:none;
          border-right:none;}
 table.sqrt {border-top:2 solid black;
             border-left:2 solid black;
             border-bottom:none;
             border-right:none;}
-->
</style>
</head>
<body>
\documentclass[12pt, a4paper]article
\title	Modelling Domestic Corruption Deterrence Through Self-Reporting and Collaborations


\authorLucas Alves Chacha
\begindocument
\maketitle
	
	The game arises when two agents, the government bureaucrat and private entrepreneur, decide whether to play or not a strategy of corruption (cooperation), constrained by probabilities of being detected and later convicted. 
	
	Given the above conditions, let: 
	
	B = Bureaucrat;
	
	E = Entrepreneur;
	
	<font face=symbol>p</font> = Advantage from corruption;
	
	b = Bribe; and 
	
	c = Cost of the bureaucrat for generating <font face=symbol>p</font>,
	
	where <font face=symbol>p</font>&gt;0 is the gain of the entrepreneur from corruption and b is the gain of the bureaucrat, such that 0&lt;b&lt;<font face=symbol>p</font>. Let the enforcement variables be: 
	
	<font face=symbol>a</font> = probability of detection; and
	
	<font face=symbol>b</font> = probability of conviction. 
	
	Finally, for i=B,E, let:
	
	S<sub>i</sub> = Sanction; and 
	
	F = Fine.
	
	For the moment, it is considered that S<sub>i</sub> is given by the gains of each player with addition of F which is the same for the payer and the receiver. Consequently, S<sub>E</sub> = <font face=symbol>p</font> +F and S<sub>B</sub> = b +F
	
	In order to derive the agent<font face=symbol>¢</font>s decision rule, and for the sake of simplicity let,
	
	p<sub>k</sub> = probability that k happens for k = <font face=symbol>p</font>, F, b,
	
	p<sub>F</sub>  <font face=symbol>º</font>  <font face=symbol>a</font> <font face=symbol>b</font> and,
	
	p<sub>b</sub> = p<sub><font face=symbol>p</font></sub>  <font face=symbol>º</font>  (1 <font face=symbol>-</font> <font face=symbol>a</font> <font face=symbol>b</font>).
	
	Under risk neutrality, the agents<font face=symbol>¢</font> utilities U<sub>i</sub> are given by the the differences between the costs and the expected benefits for each agent:
	
<table cellspacing=0  border=0 align=center>
<tr>
  <td nowrap align=center>
    U<sub>E</sub>  <font face=symbol>º</font>  <font face=symbol>-</font>b + (1<font face=symbol>-</font><font face=symbol>a</font> <font face=symbol>b</font>) <font face=symbol>p</font> <font face=symbol>-</font> <font face=symbol>a</font> <font face=symbol>b</font> F = <font face=symbol>-</font>b + p<sub><font face=symbol>p</font></sub> <font face=symbol>-</font> <font face=symbol>p</font> p<sub>F</sub> F,
  </td>
</tr>
</table>
and 
<table cellspacing=0  border=0 align=center>
<tr>
  <td nowrap align=center>
    U<sub>B</sub>  <font face=symbol>º</font>  <font face=symbol>-</font>c + (1<font face=symbol>-</font><font face=symbol>a</font> <font face=symbol>b</font>) b <font face=symbol>-</font> <font face=symbol>a</font> <font face=symbol>b</font> F= <font face=symbol>-</font>c + p<sub>b</sub> b <font face=symbol>-</font> p<sub>F</sub> F.
  </td>
</tr>
</table>
 
	
	Let us define some profitable bribery as being the fixed cost paid by agents which make their utilities at least greater than zero:
	
	
<table cellspacing=0  border=0 align=center>
<tr>
  <td nowrap align="center">
    
	b &gt;  p<sub><font face=symbol>p</font></sub> <font face=symbol>p</font><font face=symbol>-</font>  p<sub>F</sub> F,
	<a name="refprofE">
    
	<a name="eq0">&nbsp;&nbsp;&nbsp;&nbsp;<font color=blue>(0)</font>
  </td>
</tr>
</table>

	and
	
<table cellspacing=0  border=0 align=center>
<tr>
  <td nowrap align="center">
    
	c &gt;   p<sub>b</sub> b <font face=symbol>-</font> p<sub>F</sub> F,
	<a name="refprofB">
    
	<a name="eq1">&nbsp;&nbsp;&nbsp;&nbsp;<font color=blue>(1)</font>
  </td>
</tr>
</table>

	
	If fine reductions are feasible and not exploitable, then corruption is performed if profitability conditions are met. In order to calculate them in a staged game with incomplete information (<font face=symbol>g</font><sub>i</sub> &gt; 0 and <font face=symbol>w</font><sub>i</sub> &gt; 0) and distinct rules for fine reductions R and P, let:
	
	p<sub>F<sub>i</sub></sub> = f (<font face=symbol>a</font>, <font face=symbol>b</font>, <font face=symbol>g</font><sub>E</sub> , <font face=symbol>g</font><sub>B</sub>, <font face=symbol>w</font><sub>B</sub>, <font face=symbol>w</font><sub>E</sub>, P, R, p, r) , 
	p<sub>F<sub>E</sub></sub>  <font face=symbol>º</font>  <font face=symbol>a</font> <font face=symbol>G</font> (<font face=symbol>W</font> <font face=symbol>b</font> + (1<font face=symbol>-</font><font face=symbol>w</font><sub>B</sub>)<font face=symbol>w</font><sub>E</sub> P + (1<font face=symbol>-</font> <font face=symbol>w</font><sub>E</sub>)<font face=symbol>w</font><sub>B</sub> + <font face=symbol>w</font><sub>E</sub> <font face=symbol>w</font><sub>B</sub> p) + (1<font face=symbol>-</font><font face=symbol>g</font><sub>B</sub>)<font face=symbol>g</font><sub>E</sub> R + (1<font face=symbol>-</font><font face=symbol>g</font><sub>E</sub>)<font face=symbol>g</font><sub>B</sub> + <font face=symbol>g</font><sub>E</sub> <font face=symbol>g</font><sub>B</sub> r , 
	p<sub>F<sub>B</sub></sub>  <font face=symbol>º</font>  <font face=symbol>a</font> <font face=symbol>G</font> (<font face=symbol>W</font> <font face=symbol>b</font> + (1<font face=symbol>-</font><font face=symbol>w</font><sub>B</sub>)<font face=symbol>w</font><sub>E</sub>  + (1<font face=symbol>-</font> <font face=symbol>w</font><sub>E</sub>)<font face=symbol>w</font><sub>B</sub> P + <font face=symbol>w</font><sub>E</sub> <font face=symbol>w</font><sub>B</sub> p) + (1<font face=symbol>-</font><font face=symbol>g</font><sub>B</sub>)<font face=symbol>g</font><sub>E</sub> + (1<font face=symbol>-</font><font face=symbol>g</font><sub>E</sub>)<font face=symbol>g</font><sub>B</sub> R + <font face=symbol>g</font><sub>E</sub> <font face=symbol>g</font><sub>B</sub> r ,
	
	in the same way, 
	
	p<sub><font face=symbol>p</font></sub>=p<sub>b</sub> <font face=symbol>º</font>  <font face=symbol>G</font> [(1<font face=symbol>-</font><font face=symbol>a</font>) + <font face=symbol>a</font> <font face=symbol>W</font> (1<font face=symbol>-</font><font face=symbol>b</font>) ].
	
	Given that agents face the same problem of having a positive expected pay-off from collusion. Then, the constraints given by the positive probability of being reported may decrease expected pay-offs from corruption through bigger expected finesp<sub>F<sub>i</sub></sub> F and lower probability of going unpunished p<sub>b</sub> and p<sub><font face=symbol>p</font></sub> and receiving the advantage of corruption. Therefore, the decision rule for the entrepreneur can be expressed as: 
	
	 <font face=symbol>-</font>b + <font face=symbol>p</font> <font face=symbol>G</font> [(1<font face=symbol>-</font><font face=symbol>a</font>) + <font face=symbol>a</font> <font face=symbol>W</font> (1<font face=symbol>-</font><font face=symbol>b</font>)] <font face=symbol>-</font> F (<font face=symbol>a</font> <font face=symbol>G</font> (<font face=symbol>W</font> <font face=symbol>b</font> + (1<font face=symbol>-</font><font face=symbol>w</font><sub>B</sub>)<font face=symbol>w</font><sub>E</sub> P + (1<font face=symbol>-</font> <font face=symbol>w</font><sub>E</sub>)<font face=symbol>w</font><sub>B</sub> + <font face=symbol>w</font><sub>E</sub> <font face=symbol>w</font><sub>B</sub> p) + (1<font face=symbol>-</font><font face=symbol>g</font><sub>B</sub>)<font face=symbol>g</font><sub>E</sub> R + (1<font face=symbol>-</font><font face=symbol>g</font><sub>E</sub>)<font face=symbol>g</font><sub>B</sub> + <font face=symbol>g</font><sub>E</sub> <font face=symbol>g</font><sub>B</sub> r) &gt;0 , 
	
	and for the bureaucrat,
	
	 <font face=symbol>-</font>c + b <font face=symbol>G</font> [(1<font face=symbol>-</font><font face=symbol>a</font>) + <font face=symbol>a</font> <font face=symbol>W</font> (1<font face=symbol>-</font><font face=symbol>b</font>) <font face=symbol>-</font> F (<font face=symbol>a</font> <font face=symbol>G</font> (<font face=symbol>W</font> <font face=symbol>b</font> + (1<font face=symbol>-</font><font face=symbol>w</font><sub>B</sub>)<font face=symbol>w</font><sub>E</sub>  + (1<font face=symbol>-</font> <font face=symbol>w</font><sub>E</sub>)<font face=symbol>w</font><sub>B</sub> P + <font face=symbol>w</font><sub>E</sub> <font face=symbol>w</font><sub>B</sub> p) +
	(1<font face=symbol>-</font><font face=symbol>g</font><sub>B</sub>)<font face=symbol>g</font><sub>E</sub> + (1<font face=symbol>-</font><font face=symbol>g</font><sub>E</sub>)<font face=symbol>g</font><sub>B</sub> R + <font face=symbol>g</font><sub>E</sub> <font face=symbol>g</font><sub>B</sub> r) &gt; 0 . 
	
	Computing the indifference curves from the above conditions and comparing with the previous calculated ones, it is clear to see the deterrent effect of the combined policies when <font face=symbol>g</font><sub>i</sub>&gt;0 and <font face=symbol>w</font><sub>i</sub>&gt;0. The deterrence effect is given by the reduced set of combinations of the public enforcements in which corruption would be feasible. 
	
	In order to address the effect of leniencies over corruption deterrence, let <font face=symbol>q</font><sub>k</sub> be the linear coefficient that relates the k rules of fine reduction R and P to the probability of self-reporting <font face=symbol>g</font><sub>i</sub> and <font face=symbol>w</font><sub>i</sub>, in which f<font face=symbol>¢</font>(<font face=symbol>q</font><sub>k</sub>)&lt;0, and f<font face=symbol>¢</font><font face=symbol>¢</font>(<font face=symbol>q</font><sub>k</sub>)=0 such that, 
<table cellspacing=0  border=0 align=center>
<tr>
  <td nowrap align=center>
    <font face=symbol>g</font><sub>i</sub> = <font face=symbol>g</font><sub>i0</sub> <font face=symbol>-</font> <font face=symbol>q</font><sub>R</sub> R,
  </td>
</tr>
</table>
 and, 
<table cellspacing=0  border=0 align=center>
<tr>
  <td nowrap align=center>
    <font face=symbol>w</font><sub>i</sub> = <font face=symbol>w</font><sub>i0</sub> <font face=symbol>-</font> <font face=symbol>q</font><sub>P</sub> P.
  </td>
</tr>
</table>
 
	
	The same can be applied to the effect of the leniencies post detection over the probability to self-report after detection.
	
	PS: This coding uses a logistical function instead of the linear bounded function for <font face=symbol>g</font><sub>i</sub> (<font face=symbol>g</font><sub>i<sub>0</sub></sub>,R, <font face=symbol>q</font><sub>R</sub>) and <font face=symbol>w</font><sub>i</sub> (<font face=symbol>w</font><sub>i<sub>0</sub></sub>,P, <font face=symbol>q</font><sub>P</sub>)
\enddocument</body>
</html>


<!DOCTYPE html>
<html lang="en">
  
  <head>
    
      <meta charset="utf-8">
      <title>slider.py example</title>
      
      
        
          
        <link rel="stylesheet" href="https://cdn.pydata.org/bokeh/release/bokeh-1.0.2.min.css" type="text/css" />
        <link rel="stylesheet" href="https://cdn.pydata.org/bokeh/release/bokeh-widgets-1.0.2.min.css" type="text/css" />
        
        
          
        <script type="text/javascript" src="https://cdn.pydata.org/bokeh/release/bokeh-1.0.2.min.js"></script>
        <script type="text/javascript" src="https://cdn.pydata.org/bokeh/release/bokeh-widgets-1.0.2.min.js"></script>
        <script type="text/javascript">
            Bokeh.set_log_level("info");
        </script>
        
      
      
    
  </head>
  
  
  <body>
    
      
        
          
          
            
              <div class="bk-root" id="1f56dde5-0551-4562-83cb-c42cf2788199"></div>
            
          
        
      
      
        <script type="application/json" id="1226">
          {"32679937-ead7-454b-ae19-464249c1b144":{"roots":{"references":[{"attributes":{},"id":"1012","type":"BasicTicker"},{"attributes":{"callback":null,"end":1,"js_property_callbacks":{"change:value":[{"id":"1076","type":"CustomJS"}]},"start":0,"step":0.01,"title":"Theta R","value":0.001},"id":"1074","type":"Slider"},{"attributes":{},"id":"1017","type":"BasicTicker"},{"attributes":{"callback":null,"end":1,"js_property_callbacks":{"change:value":[{"id":"1076","type":"CustomJS"}]},"start":0,"step":0.01,"title":"Theta P","value":0.001},"id":"1075","type":"Slider"},{"attributes":{"dimension":1,"plot":{"id":"1002","subtype":"Figure","type":"Plot"},"ticker":{"id":"1017","type":"BasicTicker"}},"id":"1020","type":"Grid"},{"attributes":{"callback":null,"end":20,"js_property_callbacks":{"change:value":[{"id":"1076","type":"CustomJS"}]},"start":2,"title":"Bribe","value":11},"id":"1065","type":"Slider"},{"attributes":{"args":{"F":{"id":"1066","type":"Slider"},"P":{"id":"1069","type":"Slider"},"R":{"id":"1068","type":"Slider"},"b":{"id":"1065","type":"Slider"},"gammaB0":{"id":"1071","type":"Slider"},"gammaE0":{"id":"1070","type":"Slider"},"omegaB0":{"id":"1073","type":"Slider"},"omegaE0":{"id":"1072","type":"Slider"},"pi":{"id":"1067","type":"Slider"},"source":{"id":"1001","type":"ColumnDataSource"},"thetaP":{"id":"1075","type":"Slider"},"thetaR":{"id":"1074","type":"Slider"}},"code":"\n\nfunction alphaE(i,b,F,pi,R,P,gammaE0,gammaB0,omegaE0,omegaB0,thetaR,thetaP)\n{ \n    var gammaE = (2*gammaE0)/(1+Math.exp(thetaR*(R+gammaE0)));\n    var gammaB = (2*gammaB0)/(1+Math.exp(thetaR*(R+gammaB0)));\n    var omegaE = (2*omegaE0)/(1+Math.exp(thetaP*(P+omegaE0)));\n    var omegaB = (2*omegaB0)/(1+Math.exp(thetaP*(P+omegaB0)));\n    var Gamma = (1-gammaE)*(1-gammaB);\n    var B = (1-omegaE)*(1-omegaB);\n    var p= (1-(P/2));\n    var r = (1-(R/2));\n    return ((b - F*R*gammaE*gammaB + F*R*gammaE - F*gammaE*gammaB + F*gammaB - Gamma*pi + gammaE*gammaB*F*r)/\n                   ( -B*F*Gamma*i - B*Gamma*i*pi +B*Gamma*pi - F*Gamma*p*omegaE*omegaB + F*Gamma*P*omegaE*omegaB \n                     - F*Gamma*P*omegaE + F*Gamma*omegaE*omegaB - F*Gamma*omegaB - Gamma*pi));\n};\n\nfunction alphaB(j,b,F,pi,R,P,gammaE0,gammaB0,omegaE0,omegaB0,thetaR,thetaP)\n{ \n    var gammaE = (2*gammaE0)/(1+Math.exp(thetaR*(R+gammaE0)));\n    var gammaB = (2*gammaB0)/(1+Math.exp(thetaR*(R+gammaB0)));\n    var omegaE = (2*omegaE0)/(1+Math.exp(thetaP*(P+omegaE0)));\n    var omegaB = (2*omegaB0)/(1+Math.exp(thetaP*(P+omegaB0)));\n    var Gamma = (1-gammaE)*(1-gammaB);\n    var B = (1-omegaE)*(1-omegaB);\n    var p= (1-(P/2));\n    var r = (1-(R/2));\n    return ((- b*Gamma  + F*r*gammaE*gammaB - F*R*gammaE*gammaB + F*R*gammaB - F*gammaE*gammaB + F*gammaE)/\n                    (-b*B*Gamma*j + b*B*Gamma - b*Gamma - B*F*Gamma*j - F*Gamma*p*omegaE*omegaB  + F*Gamma*P*omegaE*omegaB \n                     - F*Gamma*P*omegaB + F*Gamma*omegaE*omegaB - F*Gamma*omegaE));\n};\n\n    const data = source.data;\n    const b2 = b.value;\n    const F2 = F.value;\n    const pi2 = pi.value;\n    const R2 = R.value;\n    const P2 = P.value;\n    const gammaE02 = gammaE0.value;\n    const gammaB02 = gammaB0.value;\n    const omegaE02 = omegaE0.value;\n    const omegaB02 = omegaB0.value;\n    const thetaR2 = thetaR.value;\n    const thetaP2 = thetaP.value;\n    \n    const x = data['x']\n    const y = data['y']\n    const z = data['z']\n    for (var i = 0; i &lt; x.length; i++) {\n        y[i] = alphaE(x[i],b2,F2,pi2,R2,P2,gammaE02,gammaB02,omegaE02,omegaB02,thetaR2,thetaP2);\n        z[i] = alphaB(x[i],b2,F2,pi2,R2,P2,gammaE02,gammaB02,omegaE02,omegaB02,thetaR2,thetaP2);\n    }\n\n\n  \n\n    source.change.emit();\n"},"id":"1076","type":"CustomJS"},{"attributes":{"children":[{"id":"1065","type":"Slider"}]},"id":"1077","type":"WidgetBox"},{"attributes":{"line_alpha":0.6,"line_color":"#1f77b4","line_width":3,"x":{"field":"x"},"y":{"field":"z"}},"id":"1051","type":"Line"},{"attributes":{"children":[{"id":"1077","type":"WidgetBox"},{"id":"1078","type":"WidgetBox"},{"id":"1079","type":"WidgetBox"},{"id":"1080","type":"WidgetBox"},{"id":"1081","type":"WidgetBox"},{"id":"1082","type":"WidgetBox"},{"id":"1083","type":"WidgetBox"},{"id":"1084","type":"WidgetBox"},{"id":"1085","type":"WidgetBox"},{"id":"1086","type":"WidgetBox"},{"id":"1087","type":"WidgetBox"}]},"id":"1088","type":"Column"},{"attributes":{"line_alpha":0.1,"line_color":"#1f77b4","line_width":3,"x":{"field":"x"},"y":{"field":"y"}},"id":"1038","type":"Line"},{"attributes":{"line_alpha":0.1,"line_color":"#1f77b4","line_width":3,"x":{"field":"x"},"y":{"field":"z"}},"id":"1052","type":"Line"},{"attributes":{"data_source":{"id":"1001","type":"ColumnDataSource"},"glyph":{"id":"1037","type":"Line"},"hover_glyph":null,"muted_glyph":null,"nonselection_glyph":{"id":"1038","type":"Line"},"selection_glyph":null,"view":{"id":"1040","type":"CDSView"}},"id":"1039","type":"GlyphRenderer"},{"attributes":{"data_source":{"id":"1001","type":"ColumnDataSource"},"glyph":{"id":"1051","type":"Line"},"hover_glyph":null,"muted_glyph":null,"nonselection_glyph":{"id":"1052","type":"Line"},"selection_glyph":null,"view":{"id":"1054","type":"CDSView"}},"id":"1053","type":"GlyphRenderer"},{"attributes":{"children":[{"id":"1066","type":"Slider"}]},"id":"1078","type":"WidgetBox"},{"attributes":{"source":{"id":"1001","type":"ColumnDataSource"}},"id":"1054","type":"CDSView"},{"attributes":{"callback":null,"end":40,"js_property_callbacks":{"change:value":[{"id":"1076","type":"CustomJS"}]},"start":2,"title":"Fine","value":21},"id":"1066","type":"Slider"},{"attributes":{"children":[{"id":"1067","type":"Slider"}]},"id":"1079","type":"WidgetBox"},{"attributes":{},"id":"1021","type":"PanTool"},{"attributes":{},"id":"1061","type":"UnionRenderers"},{"attributes":{"below":[{"id":"1011","type":"LinearAxis"}],"left":[{"id":"1016","type":"LinearAxis"}],"plot_height":700,"plot_width":700,"renderers":[{"id":"1011","type":"LinearAxis"},{"id":"1015","type":"Grid"},{"id":"1016","type":"LinearAxis"},{"id":"1020","type":"Grid"},{"id":"1029","type":"BoxAnnotation"},{"id":"1048","type":"Legend"},{"id":"1039","type":"GlyphRenderer"},{"id":"1053","type":"GlyphRenderer"}],"title":{"id":"1042","type":"Title"},"toolbar":{"id":"1027","type":"Toolbar"},"x_range":{"id":"1003","type":"Range1d"},"x_scale":{"id":"1007","type":"LinearScale"},"y_range":{"id":"1005","type":"Range1d"},"y_scale":{"id":"1009","type":"LinearScale"}},"id":"1002","subtype":"Figure","type":"Plot"},{"attributes":{"children":[{"id":"1068","type":"Slider"}]},"id":"1080","type":"WidgetBox"},{"attributes":{},"id":"1022","type":"WheelZoomTool"},{"attributes":{},"id":"1062","type":"Selection"},{"attributes":{"children":[{"id":"1069","type":"Slider"}]},"id":"1081","type":"WidgetBox"},{"attributes":{"overlay":{"id":"1029","type":"BoxAnnotation"}},"id":"1023","type":"BoxZoomTool"},{"attributes":{"label":{"value":"Bureaucrat"},"renderers":[{"id":"1053","type":"GlyphRenderer"}]},"id":"1064","type":"LegendItem"},{"attributes":{"callback":null,"data":{"x":{"__ndarray__":"/Knx0k1iUD/L+y1kAYuVP3tulvXuB6U/EN8VOV1Krz/Tp0q+Zca0Px5gCuCc57k/aBjKAdQIvz9a6MSRBRXCP3/EpCKhpcQ/pKCEszw2xz/KfGRE2MbJP+9YRNVzV8w/FDUkZg/ozj+dCIJ7VbzQP7D28UOjBNI/wuRhDPFM0z/V0tHUPpXUP+jAQZ2M3dU/+q6xZdol1z8NnSEuKG7YPyCLkfZ1ttk/MnkBv8P+2j9FZ3GHEUfcP1hV4U9fj90/akNRGK3X3j+/mGBw/Q/gP8iPmFQktOA/0YbQOEtY4T/bfQgdcvzhP+R0QAGZoOI/7Wt45b9E4z/3YrDJ5ujjPwBa6K0NjeQ/CVEgkjQx5T8TSFh2W9XlPxw/kFqCeeY/JTbIPqkd5z8vLQAj0MHnPzgkOAf3Zeg/QRtw6x0K6T9LEqjPRK7pP1QJ4LNrUuo/XQAYmJL26j9n9098uZrrP3Duh2DgPuw/eeW/RAfj7D+D3PcoLoftP4zTLw1VK+4/lcpn8XvP7j+fwZ/VonPvP1Tc69zkC/A/2NcHT/hd8D9d0yPBC7DwP+LOPzMfAvE/ZspbpTJU8T/rxXcXRqbxP3DBk4lZ+PE/9Lyv+2xK8j95uMttgJzyP/6z59+T7vI/gq8DUqdA8z8Hqx/EupLzP4ymOzbO5PM/EKJXqOE29D+VnXMa9Yj0PxqZj4wI2/Q/npSr/hst9T8jkMdwL3/1P6iL4+JC0fU/LIf/VFYj9j+xghvHaXX2PzZ+Nzl9x/Y/unlTq5AZ9z8/dW8dpGv3P8Rwi4+3vfc/SGynAcsP+D/NZ8Nz3mH4P1Jj3+Xxs/g/1l77VwUG+T9bWhfKGFj5P+BVMzwsqvk/ZFFPrj/8+T/pTGsgU076P25Ih5JmoPo/8kOjBHry+j93P792jUT7P/w62+iglvs/gDb3WrTo+z8FMhPNxzr8P4otLz/bjPw/DilLse7e/D+TJGcjAjH9Pxggg5UVg/0/nBufBynV/T8hF7t5PCf+P6YS1+tPef4/Kg7zXWPL/j+vCQ/Qdh3/PzQFK0KKb/8/uQBHtJ3B/z8ffjGT2AkAQOF7P0ziMgBAo3lNBexbAEBmd1u+9YQAQCh1aXf/rQBA6nJ3MAnXAECtcIXpEgABQG9uk6IcKQFAMWyhWyZSAUD0aa8UMHsBQLZnvc05pAFAeGXLhkPNAUA7Y9k/TfYBQP1g5/hWHwJAv171sWBIAkCCXANranECQERaESR0mgJABlgf3X3DAkDJVS2Wh+wCQItTO0+RFQNATVFJCJs+A0AQT1fBpGcDQNJMZXqukANAlEpzM7i5A0BXSIHsweIDQBlGj6XLCwRA20OdXtU0BECeQasX310EQGA/udDohgRAIj3HifKvBEDlOtVC/NgEQKc44/sFAgVAaTbxtA8rBUAsNP9tGVQFQO4xDScjfQVAsC8b4CymBUBzLSmZNs8FQDUrN1JA+AVA9yhFC0ohBkC6JlPEU0oGQHwkYX1dcwZAPiJvNmecBkABIH3vcMUGQMMdi6h67gZAhRuZYYQXB0BIGacajkAHQAoXtdOXaQdAzBTDjKGSB0CPEtFFq7sHQFEQ3/605AdAEw7tt74NCEDWC/twyDYIQJgJCSrSXwhAWgcX49uICEAdBSWc5bEIQN8CM1Xv2ghAoQBBDvkDCUBk/k7HAi0JQCb8XIAMVglA6PlqORZ/CUCr93jyH6gJQG31hqsp0QlAL/OUZDP6CUDy8KIdPSMKQLTusNZGTApAduy+j1B1CkA56sxIWp4KQPvn2gFkxwpAveXoum3wCkCA4/ZzdxkLQELhBC2BQgtABN8S5oprC0DH3CCflJQLQInaLlievQtAS9g8EajmC0AO1krKsQ8MQNDTWIO7OAxAktFmPMVhDEBVz3T1zooMQBfNgq7YswxA2cqQZ+LcDECcyJ4g7AUNQF7GrNn1Lg1AIMS6kv9XDUDjwchLCYENQKW/1gQTqg1AZ73kvRzTDUAqu/J2JvwNQOy4ADAwJQ5ArrYO6TlODkBxtByiQ3cOQDOyKltNoA5A9a84FFfJDkC4rUbNYPIOQHqrVIZqGw9APaliP3RED0D/pnD4fW0PQMGkfrGHlg9AhKKMapG/D0BGoJojm+gPQAVPVG7SCBBA5k3bSlcdEEDHTGIn3DEQQKhL6QNhRhBAiUpw4OVaEEBqSfe8am8QQExIfpnvgxBALUcFdnSYEEAORoxS+awQQO9EEy9+wRBA0EOaCwPWEECxQiHoh+oQQJNBqMQM/xBAdEAvoZETEUBVP7Z9FigRQDY+PVqbPBFAFz3ENiBREUD4O0sTpWURQNo60u8pehFAuzlZzK6OEUCcOOCoM6MRQH03Z4W4txFAXjbuYT3MEUA/NXU+wuARQCE0/BpH9RFAAjOD98sJEkDjMQrUUB4SQMQwkbDVMhJApS8YjVpHEkCGLp9p31sSQGgtJkZkcBJASSytIumEEkAqKzT/bZkSQAsqu9vyrRJA7ChCuHfCEkDNJ8mU/NYSQK8mUHGB6xJAkCXXTQYAE0BxJF4qixQTQFIj5QYQKRNAMyJs45Q9E0AUIfO/GVITQPYfepyeZhNA1x4BeSN7E0C4HYhVqI8TQJkcDzItpBNAehuWDrK4E0BbGh3rNs0TQD0ZpMe74RNAHhgrpED2E0D/FrKAxQoUQOAVOV1KHxRAwRTAOc8zFECiE0cWVEgUQIQSzvLYXBRAZRFVz11xFEBGENyr4oUUQCcPY4hnmhRACA7qZOyuFEDqDHFBccMUQMsL+B321xRArAp/+nrsFECNCQbX/wAVQG4IjbOEFRVATwcUkAkqFUAxBptsjj4VQBIFIkkTUxVA8wOpJZhnFUDUAjACHXwVQLUBt96hkBVAlgA+uyalFUB4/8SXq7kVQFn+S3QwzhVAOv3SULXiFUAb/FktOvcVQPz64Am/CxZA3fln5kMgFkC/+O7CyDQWQKD3dZ9NSRZAgfb8e9JdFkBi9YNYV3IWQEP0CjXchhZAJPOREWGbFkAG8hju5a8WQOfwn8pqxBZAyO8mp+/YFkCp7q2DdO0WQIrtNGD5ARdAa+y7PH4WF0BN60IZAysXQC7qyfWHPxdAD+lQ0gxUF0Dw59eukWgXQNHmXosWfRdAsuXlZ5uRF0CU5GxEIKYXQHXj8yCluhdAVuJ6/SnPF0A34QHaruMXQBjgiLYz+BdA+d4Pk7gMGEDb3ZZvPSEYQLzcHUzCNRhAndukKEdKGEB+2isFzF4YQF/ZsuFQcxhAQNg5vtWHGEAi18CaWpwYQAPWR3ffsBhA5NTOU2TFGEDF01Uw6dkYQKbS3Axu7hhAh9Fj6fICGUBp0OrFdxcZQErPcaL8KxlAK874foFAGUAMzX9bBlUZQO3LBjiLaRlAzsqNFBB+GUCwyRTxlJIZQJHIm80ZpxlAcsciqp67GUBTxqmGI9AZQDTFMGOo5BlAFcS3Py35GUD3wj4csg0aQNjBxfg2IhpAucBM1bs2GkCav9OxQEsaQHu+Wo7FXxpAXL3hakp0GkA+vGhHz4gaQB+77yNUnRpAALp2ANmxGkDhuP3cXcYaQMK3hLni2hpAo7YLlmfvGkCFtZJy7AMbQGa0GU9xGBtAR7OgK/YsG0AosicIe0EbQAmxruT/VRtA6q81wYRqG0DMrrydCX8bQK2tQ3qOkxtAjqzKVhOoG0Bvq1EzmLwbQFCq2A8d0RtAMalf7KHlG0ATqObIJvobQPSmbaWrDhxA1aX0gTAjHEC2pHtetTccQJejAjs6TBxAeKKJF79gHEBaoRD0Q3UcQDugl9DIiRxAHJ8erU2eHED9naWJ0rIcQN6cLGZXxxxAv5uzQtzbHEChmjofYfAcQIKZwfvlBB1AY5hI2GoZHUBEl8+07y0dQCWWVpF0Qh1ABpXdbflWHUDok2RKfmsdQMmS6yYDgB1AqpFyA4iUHUCLkPnfDKkdQGyPgLyRvR1ATY4HmRbSHUAvjY51m+YdQBCMFVIg+x1A8YqcLqUPHkDSiSMLKiQeQLOIqueuOB5AlIcxxDNNHkB2hriguGEeQFeFP309dh5AOITGWcKKHkAZg002R58eQPqB1BLMsx5A24Bb71DIHkC9f+LL1dweQJ5+aaha8R5Af33whN8FH0BgfHdhZBofQEF7/j3pLh9AI3qFGm5DH0AEeQz38lcfQOV3k9N3bB9AxnYasPyAH0CndaGMgZUfQIh0KGkGqh9AanOvRYu+H0BLcjYiENMfQCxxvf6U5x9ADXBE2xn8H0B3t+VbTwggQOc2KcqREiBAWLZsONQcIEDINbCmFicgQDm18xRZMSBAqjQ3g5s7IEAatHrx3UUgQIszvl8gUCBA+7IBzmJaIEBsMkU8pWQgQNyxiKrnbiBATTHMGCp5IEC+sA+HbIMgQC4wU/WujSBAn6+WY/GXIEAPL9rRM6IgQICuHUB2rCBA8S1hrri2IEBhraQc+8AgQNIs6Io9yyBAQqwr+X/VIECzK29nwt8gQCOrstUE6iBAlCr2Q0f0IEAFqjmyif4gQHUpfSDMCCFA5qjAjg4TIUBWKAT9UB0hQMenR2uTJyFAOCeL2dUxIUCops5HGDwhQBkmErZaRiFAiaVVJJ1QIUD6JJmS31ohQGqk3AAiZSFA2yMgb2RvIUBMo2PdpnkhQLwip0vpgyFALaLquSuOIUCdIS4obpghQA6hcZawoiFAfyC1BPOsIUDvn/hyNbchQGAfPOF3wSFA0J5/T7rLIUBBHsO9/NUhQLGdBiw/4CFAIh1KmoHqIUCTnI0IxPQhQAMc0XYG/yFAdJsU5UgJIkDkGlhTixMiQFWam8HNHSJAxhnfLxAoIkA2mSKeUjIiQKcYZgyVPCJAF5ipetdGIkCIF+3oGVEiQPiWMFdcWyJAaRZ0xZ5lIkDalbcz4W8iQEoV+6EjeiJAu5Q+EGaEIkArFIJ+qI4iQJyTxezqmCJADRMJWy2jIkB9kkzJb60iQO4RkDeytyJAXpHTpfTBIkDPEBcUN8wiQD+QWoJ51iJAsA+e8LvgIkAhj+Fe/uoiQJEOJc1A9SJAAo5oO4P/IkByDaypxQkjQOOM7xcIFCNAVAwzhkoeI0DEi3b0jCgjQDULumLPMiNApYr90BE9I0AWCkE/VEcjQIaJhK2WUSNA9wjIG9lbI0BoiAuKG2YjQNgHT/hdcCNASYeSZqB6I0C5BtbU4oQjQCqGGUMljyNAmwVdsWeZI0ALhaAfqqMjQHwE5I3srSNA7IMn/C64I0BdA2tqccIjQM2CrtizzCNAPgLyRvbWI0CvgTW1OOEjQB8BeSN76yNAkIC8kb31I0AAAAAAAAAkQA==","dtype":"float64","shape":[500]},"y":{"__ndarray__":"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","dtype":"float64","shape":[500]},"z":{"__ndarray__":"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","dtype":"float64","shape":[500]}},"selected":{"id":"1062","type":"Selection"},"selection_policy":{"id":"1061","type":"UnionRenderers"}},"id":"1001","type":"ColumnDataSource"},{"attributes":{"children":[{"id":"1070","type":"Slider"}]},"id":"1082","type":"WidgetBox"},{"attributes":{},"id":"1024","type":"SaveTool"},{"attributes":{"callback":null},"id":"1003","type":"Range1d"},{"attributes":{"line_alpha":0.6,"line_width":3,"x":{"field":"x"},"y":{"field":"y"}},"id":"1037","type":"Line"},{"attributes":{"children":[{"id":"1071","type":"Slider"}]},"id":"1083","type":"WidgetBox"},{"attributes":{},"id":"1025","type":"ResetTool"},{"attributes":{"callback":null,"end":40,"js_property_callbacks":{"change:value":[{"id":"1076","type":"CustomJS"}]},"start":4,"title":"Entrepreneur Advatage","value":22},"id":"1067","type":"Slider"},{"attributes":{"children":[{"id":"1072","type":"Slider"}]},"id":"1084","type":"WidgetBox"},{"attributes":{},"id":"1026","type":"HelpTool"},{"attributes":{"callback":null},"id":"1005","type":"Range1d"},{"attributes":{"callback":null,"end":1,"js_property_callbacks":{"change:value":[{"id":"1076","type":"CustomJS"}]},"start":-1,"step":0.01,"title":"Fine Reduction for Self-Reporting Before Detection","value":1},"id":"1068","type":"Slider"},{"attributes":{"active_drag":"auto","active_inspect":"auto","active_multi":null,"active_scroll":"auto","active_tap":"auto","tools":[{"id":"1021","type":"PanTool"},{"id":"1022","type":"WheelZoomTool"},{"id":"1023","type":"BoxZoomTool"},{"id":"1024","type":"SaveTool"},{"id":"1025","type":"ResetTool"},{"id":"1026","type":"HelpTool"}]},"id":"1027","type":"Toolbar"},{"attributes":{"children":[{"id":"1073","type":"Slider"}]},"id":"1085","type":"WidgetBox"},{"attributes":{},"id":"1007","type":"LinearScale"},{"attributes":{"source":{"id":"1001","type":"ColumnDataSource"}},"id":"1040","type":"CDSView"},{"attributes":{"callback":null,"end":1,"js_property_callbacks":{"change:value":[{"id":"1076","type":"CustomJS"}]},"start":-1,"step":0.01,"title":"Fine Reduction for Self-Reporting After Detection","value":1},"id":"1069","type":"Slider"},{"attributes":{"children":[{"id":"1074","type":"Slider"}]},"id":"1086","type":"WidgetBox"},{"attributes":{},"id":"1046","type":"BasicTickFormatter"},{"attributes":{},"id":"1009","type":"LinearScale"},{"attributes":{"bottom_units":"screen","fill_alpha":{"value":0.5},"fill_color":{"value":"lightgrey"},"left_units":"screen","level":"overlay","line_alpha":{"value":1.0},"line_color":{"value":"black"},"line_dash":[4,4],"line_width":{"value":2},"plot":null,"render_mode":"css","right_units":"screen","top_units":"screen"},"id":"1029","type":"BoxAnnotation"},{"attributes":{"callback":null,"end":1,"js_property_callbacks":{"change:value":[{"id":"1076","type":"CustomJS"}]},"start":0,"step":0.01,"title":"Probability of the Entrepreneur Self-Reporting - Before","value":0.1},"id":"1070","type":"Slider"},{"attributes":{"children":[{"id":"1075","type":"Slider"}]},"id":"1087","type":"WidgetBox"},{"attributes":{"formatter":{"id":"1044","type":"BasicTickFormatter"},"plot":{"id":"1002","subtype":"Figure","type":"Plot"},"ticker":{"id":"1012","type":"BasicTicker"}},"id":"1011","type":"LinearAxis"},{"attributes":{"plot":null,"text":""},"id":"1042","type":"Title"},{"attributes":{"callback":null,"end":1,"js_property_callbacks":{"change:value":[{"id":"1076","type":"CustomJS"}]},"start":0,"step":0.01,"title":"Probability of the Bureaucrat Self-Reporting - Before","value":0.1},"id":"1071","type":"Slider"},{"attributes":{"children":[{"id":"1002","subtype":"Figure","type":"Plot"},{"id":"1088","type":"Column"}]},"id":"1089","type":"Row"},{"attributes":{},"id":"1044","type":"BasicTickFormatter"},{"attributes":{"label":{"value":"Entrepreneur"},"renderers":[{"id":"1039","type":"GlyphRenderer"}]},"id":"1049","type":"LegendItem"},{"attributes":{"callback":null,"end":1,"js_property_callbacks":{"change:value":[{"id":"1076","type":"CustomJS"}]},"start":0,"step":0.01,"title":"Probability of the Entrepreneur Self-Reporting - After","value":0.1},"id":"1072","type":"Slider"},{"attributes":{"plot":{"id":"1002","subtype":"Figure","type":"Plot"},"ticker":{"id":"1012","type":"BasicTicker"}},"id":"1015","type":"Grid"},{"attributes":{"callback":null,"end":1,"js_property_callbacks":{"change:value":[{"id":"1076","type":"CustomJS"}]},"start":0,"step":0.01,"title":"Probability of the Bureaucrat Self-Reporting - After","value":0.1},"id":"1073","type":"Slider"},{"attributes":{"items":[{"id":"1049","type":"LegendItem"},{"id":"1064","type":"LegendItem"}],"plot":{"id":"1002","subtype":"Figure","type":"Plot"}},"id":"1048","type":"Legend"},{"attributes":{"formatter":{"id":"1046","type":"BasicTickFormatter"},"plot":{"id":"1002","subtype":"Figure","type":"Plot"},"ticker":{"id":"1017","type":"BasicTicker"}},"id":"1016","type":"LinearAxis"}],"root_ids":["1089"]},"title":"Bokeh Application","version":"1.0.2"}}
        </script>
        <script type="text/javascript">
          (function() {
            var fn = function() {
              Bokeh.safely(function() {
                (function(root) {
                  function embed_document(root) {
                    
                  var docs_json = document.getElementById('1226').textContent;
                  var render_items = [{"docid":"32679937-ead7-454b-ae19-464249c1b144","roots":{"1089":"1f56dde5-0551-4562-83cb-c42cf2788199"}}];
                  root.Bokeh.embed.embed_items(docs_json, render_items);
                
                  }
                  if (root.Bokeh !== undefined) {
                    embed_document(root);
                  } else {
                    var attempts = 0;
                    var timer = setInterval(function(root) {
                      if (root.Bokeh !== undefined) {
                        embed_document(root);
                        clearInterval(timer);
                      }
                      attempts++;
                      if (attempts > 100) {
                        console.log("Bokeh: ERROR: Unable to run BokehJS code because BokehJS library is missing");
                        clearInterval(timer);
                      }
                    }, 10, root)
                  }
                })(window);
              });
            };
            if (document.readyState != "loading") fn();
            else document.addEventListener("DOMContentLoaded", fn);
          })();
        </script>
    
  </body>
  
</html>
