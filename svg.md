<svg viewBox="80 -60 860 665" width="11in" height="816" xmlns="http://www.w3.org/2000/svg" aria-labelledby="svgTitle" aria-describedby="svgDesc">
  <defs>
    <pattern id="waterPattern" patternUnits="userSpaceOnUse" width="20" height="20" viewBox="0 0 10 10">
      <path d="M0 5c2.5-2.5 7.5-2.5 10 0s7.5 2.5 10 0" stroke="#6495ed" fill="none"/>
    </pattern>
    <pattern id="brickPatternOutline" patternUnits="userSpaceOnUse" width="30" height="16" viewBox="0 0 30 16">
      <path fill="#f5f5f5" d="M0 0h30v16H0z"/>
      <path fill="none" stroke="#a9a9a9" stroke-width=".7" d="M0 0h14v7H0zm15 0h14v7H15zM-7.5 8h14v7h-14zm15 0h14v7h-14zm15 0h14v7h-14z"/>
    </pattern>
    <symbol id="houseIcon" viewBox="0 0 100 100">
      <path d="M50 10 10 40v50h30V60h20v30h30V40Z" fill="none" stroke="#333" stroke-width="5"/>
    </symbol>
    <symbol id="doorIcon" viewBox="0 0 20 40">
      <rect x="2" y="2" width="16" height="36" fill="#f5f5f5" stroke="#333" stroke-width="1.5" rx="2"/>
      <circle cx="15" cy="20" r="1.5" fill="#333"/>
    </symbol>
  </defs>
  <title id="svgTitle">Land Map - Vehari Area</title>
  <desc id="svgDesc">
    A map showing land plots, ownership, common areas, and features. Dimension labels (e.g., &apos;220x198ft&apos;) have been removed from all plots. The right filler box contains a table with details from Khewat Number 202. The filler boxes align vertically with the N-plots. Plots N1-N5 and the compass are positioned above the Main Road. Common Passage 1 and Common Passage 2 are styled with a colorless brick outline pattern. Other features include a water body, drainage channels, and a Haveli. Plots 4, 14, 24, and 34 have been widened by extending their left boundaries to meet the central water course.
  </desc>
  <style>
    <![CDATA[text{font-family:"Helvetica Neue","Segoe UI",Helvetica,Arial,sans-serif;dominant-baseline:middle;text-anchor:middle;fill:#000;opacity:1;letter-spacing:.3px;text-rendering:geometricPrecision;shape-rendering:crispEdges}.plot-number{font-size:14px;font-weight:600;letter-spacing:.5px;fill:#000}.owner-name{font-size:12px;font-weight:400;fill:#2c2c2c;letter-spacing:.2px}.common-area{font-size:14px;font-weight:600;fill:#000;letter-spacing:.8px;text-transform:uppercase}.caption{font-size:11px;font-weight:400;fill:#3a3a3a;letter-spacing:.2px}.plot-group:hover>path,.plot-group:hover>rect{filter:brightness(95%)}.irrelevant-plot-fill{fill:#fdfd96}]]>
  </style>
  <g id="main-road">
    <title>Main Road</title>
    <path fill="khaki" stroke="#333" stroke-width="1.5" d="M100-40h800v60H100z"/>
    <text x="500" y="-10" class="common-area">Main Road</text>
  </g>
  <g id="plot-N4-old" class="plot-group">
    <title>Plot N4-old</title>
    <path class="irrelevant-plot-fill" stroke="#333" stroke-width="1.5" d="M100 20h267v100H100z"/>
    <text x="233.5" y="55" class="plot-number">N4</text>
    <text x="233.5" y="75" class="caption" font-size="9">(out of Khewat 202)</text>
  </g>
  <g id="plot-Out of Khewat 202" class="plot-group">
    <title>Plot Out of Khewat 202</title>
    <path class="irrelevant-plot-fill" stroke="#333" stroke-width="1.5" d="M367 20h133v100H367z"/>
    <text x="433.5" y="55" class="plot-number">Out of</text>
    <text x="433.5" y="72" class="plot-number">Khewat 202</text>
  </g>
  <g id="plot-38" class="plot-group">
    <title>Plot 38 (Increased Width, Subdivided)</title>
    <path fill="#fff" stroke="#333" stroke-width="1.5" d="M500 20h118v100H500z"/>
    <path stroke="#666" stroke-dasharray="4,2" d="M500 50h118M500 70h118M500 90h118m-118 20h118"/>
    <text x="559" y="30" font-size="10" font-weight="700" text-rendering="geometricPrecision">Khangi Wanda</text>
    <text x="559" y="43" class="caption" font-size="8">(alternate Khewat 219)</text>
  </g>
  <g id="common-passage-1">
    <title>Common Passage 1 (Brick Outline Pathway)</title>
    <path fill="url(#brickPatternOutline)" stroke="#333" stroke-width="1.5" opacity=".5" d="M618 20h15v180h-15z"/>
    <rect x="620" y="65" width="11" height="90" fill="#fff" opacity=".85" rx="1"/>
    <text x="625.5" y="110" font-size="11" font-weight="700" text-rendering="geometricPrecision" transform="rotate(90 625.5 110)">Common Passage (11.5 ft)</text>
  </g>
  <g id="Khewat 219 Joint Khewat" class="plot-group">
    <title>Khewat 219 Joint Khewat (Haveli) - Khewat 219</title>
    <path d="M633 20h133v100H633V80m0-20V20Z" fill="#fff8dc" stroke="#333" stroke-width="1.5"/>
    <use href="#doorIcon" x="633" y="60" width="10" height="20" transform="translate(-5)"/>
    <text x="700" y="42" class="plot-number">Joint Khewat</text>
    <text x="700" y="58" class="plot-number">219</text>
    <text x="700" y="75" class="owner-name">(Haveli)</text>
    <text x="700" y="90" class="caption" font-size="9">Original Chah Dor</text>
    <use href="#houseIcon" x="675" y="95" width="50" height="50"/>
  </g>
  <g id="plot-41" class="plot-group">
    <title>Plot 41</title>
    <path class="irrelevant-plot-fill" stroke="#333" stroke-width="1.5" d="M100 120h133v80H100z"/>
    <text x="166.5" y="145" class="plot-number">125/25</text>
    <text x="166.5" y="165" class="caption" font-size="9">(out of Khewat 202)</text>
  </g>
  <g id="plot-42" class="plot-group">
    <title>Plot 42</title>
    <path class="irrelevant-plot-fill" stroke="#333" stroke-width="1.5" d="M233 120h134v80H233z"/>
    <text x="300" y="145" class="plot-number">125/24</text>
    <text x="300" y="165" class="caption" font-size="9">(out of Khewat 202)</text>
  </g>
  <g id="plot-43" class="plot-group">
    <title>Plot 43 - Owner: Khanshmir etc.</title>
    <path fill="#fff" stroke="#333" stroke-width="1.5" d="M367 120h133v80H367z"/>
    <text x="433.5" y="135" class="plot-number">125/23</text>
    <text x="433.5" y="153" class="owner-name">Khanshmir etc.</text>
  </g>
  <g id="plot-44" class="plot-group">
    <title>Plot 44 (Increased Width) - Owner: Khanshmir etc.</title>
    <path fill="#fff" stroke="#333" stroke-width="1.5" d="M500 120h118v80H500z"/>
    <text x="559" y="135" class="plot-number">125/22</text>
    <text x="559" y="153" class="owner-name">Khanshmir etc.</text>
  </g>
  <g id="plot-125/21" class="plot-group">
    <title>125/21 - Subdivided: 125/21A (Khanshmir etc. - House), 125/21B (Aish/Mushtaq etc.)</title>
    <path fill="#fff" stroke="#333" stroke-width="1.5" d="M633 120h133v80H633z"/>
    <path stroke="#666" stroke-dasharray="4,2" d="M700 120v80"/>
    <g id="plot-125/21A">
      <title>Plot 125/21A - Owner: Khanshmir etc. (House)</title>
      <use href="#houseIcon" x="638" y="125" width="15" height="15"/>
      <text x="666.5" y="150" class="plot-number">125/21A</text>
      <text x="666.5" y="168" class="owner-name">Khan-</text>
      <text x="666.5" y="183" class="owner-name">shamir</text>
    </g>
    <g id="plot-125/21B">
      <title>Plot 125/21B - Owner: Aish/Mushtaq etc.</title>
      <text x="733.5" y="150" class="plot-number">125/21B</text>
      <text x="733.5" y="168" class="owner-name">Aish</text>
      <text x="733.5" y="183" class="owner-name">Mushtaq etc.</text>
    </g>
  </g>
  <g id="plot-124/25" class="plot-group">
    <title>Plot 46 - Subdivided: 124/25A (Aish/Mushtaq etc.), 124/25B (Ilam Din/Qutab Din etc.)</title>
    <path fill="#fff" stroke="#333" stroke-width="1.5" d="M766 120h134v80H766z"/>
    <path stroke="#666" stroke-dasharray="4,2" d="M766 160h134"/>
    <g id="plot-124/25A">
      <title>Plot 124/25A - Owner: Aish/Mushtaq etc.</title>
      <text x="833" y="135" class="plot-number">124/25A</text>
      <text x="833" y="150" class="owner-name">Aish/Mushtaq etc.</text>
    </g>
    <g id="plot-124/25B">
      <title>Plot 124/25B - Owner: Ilam Din/Qutab Din etc.</title>
      <text x="833" y="175" class="plot-number">124/25B</text>
      <text x="833" y="190" class="owner-name">Ilam Din/Qutab Din etc.</text>
    </g>
  </g>
  <g id="common-passage-2-integrated">
    <title>Common Passage 2 (Brick Outline Pathway) - Integrated</title>
    <path fill="url(#brickPatternOutline)" stroke="#333" stroke-width="1.5" opacity=".3" d="M367 200h466v20H367z"/>
    <rect x="540" y="203" width="120" height="14" fill="#fff" opacity=".85" rx="1"/>
    <text x="600" y="210" font-size="10" font-weight="700" text-rendering="geometricPrecision">Common Passage (11.5 ft)</text>
  </g>
  <g id="plot-1" class="plot-group">
    <title>Plot 1</title>
    <path class="irrelevant-plot-fill" stroke="#333" stroke-width="1.5" d="M100 200h133v80H100z"/>
    <text x="166.5" y="225" class="plot-number">125/16</text>
    <text x="166.5" y="245" class="caption" font-size="9">(out of Khewat 202)</text>
  </g>
  <g id="plot-2" class="plot-group">
    <title>Plot 2 - Owner: Khanshmir etc.</title>
    <path fill="#fff" stroke="#333" stroke-width="1.5" d="M233 200h134v80H233z"/>
    <text x="300" y="220" class="plot-number">125/17</text>
    <text x="300" y="240" class="owner-name">Khanshmir etc.</text>
  </g>
  <g id="plot-3" class="plot-group">
    <title>Plot 3 - Owner: Sarmed/Zamad etc. (Reduced Height &amp; Width)</title>
    <path fill="#fff" stroke="#333" stroke-width="1.5" d="M367 220h123v60H367z"/>
    <text x="428.5" y="235" class="plot-number">125/18</text>
    <text x="428.5" y="250" class="owner-name">Sarmed/Zamad etc.</text>
  </g>
  <g id="plot-4" class="plot-group">
    <title>Plot 4 - Owner: Ilam Din/Qutab Din etc. (Adjusted Width, Reduced Height)</title>
    <path fill="#fff" stroke="#333" stroke-width="1.5" d="M500 220h138v60H500z"/>
    <text x="569" y="235" class="plot-number">125/19</text>
    <text x="569" y="250" class="owner-name">Ilam Din/Qutab Din etc.</text>
  </g>
  <g id="plot-5" class="plot-group">
    <title>Plot 5 - Owner: Naved/Shafiq etc. (Reduced Height)</title>
    <path fill="#fff" stroke="#333" stroke-width="1.5" d="M633 220h133v60H633z"/>
    <text x="700" y="235" class="plot-number">125/20</text>
    <text x="700" y="250" class="owner-name">Naved/Shafiq etc.</text>
  </g>
  <g id="plot-6" class="plot-group">
    <title>Plot 6 - Subdivided: 6A (Naved/Shafiq etc.), 6B (Sarmed/Zamad etc.)</title>
    <path fill="none" d="M766 200h134v80H766z"/>
    <path stroke="#666" stroke-dasharray="4,2" d="M833 220v60"/>
    <g id="plot-6A">
      <title>Plot 6A - Owner: Naved/Shafiq etc. (Reduced Height)</title>
      <path fill="#fff" stroke="#333" stroke-width="1.5" d="M766 220h67v60h-67z"/>
      <text x="800" y="235" class="plot-number">124/16A</text>
      <text x="800" y="252" class="owner-name">Naved/</text>
      <text x="800" y="265" class="owner-name">Shafiq etc.</text>
    </g>
    <g id="plot-6B">
      <title>Plot 6B - Owner: Sarmed/Zamad etc. (Standard Height)</title>
      <path fill="#fff" stroke="#333" stroke-width="1.5" d="M833 200h67v80h-67z"/>
      <text x="866" y="218" class="plot-number">124/16B</text>
      <text x="866" y="235" class="owner-name">Sarmed/</text>
      <text x="866" y="248" class="owner-name">Zamad etc.</text>
    </g>
  </g>
  <g id="central-water-course">
    <title>Central Water Course</title>
    <path fill="url(#waterPattern)" stroke="#333" stroke-width="1.5" d="M490 220h10v320h-10z"/>
    <path fill="rgba(173, 216, 230, 0.6)" stroke="#333" stroke-width="1.5" d="M490 220h10v320h-10z"/>
  </g>
  <g id="plot-11" class="plot-group">
    <title>Plot 11 - Owner: Yameen</title>
    <path class="irrelevant-plot-fill" stroke="#333" stroke-width="1.5" d="M100 280h133v80H100z"/>
    <text x="166.5" y="295" class="plot-number">125/15</text>
    <text x="166.5" y="315" class="owner-name">Yameen</text>
    <text x="166.5" y="330" class="caption" font-size="9">(out of Khewat 202)</text>
  </g>
  <g id="plot-12" class="plot-group">
    <title>Plot 12 - Owner: Khanshmir etc.</title>
    <path fill="#fff" stroke="#333" stroke-width="1.5" d="M233 280h134v80H233z"/>
    <text x="300" y="300" class="plot-number">125/14</text>
    <text x="300" y="320" class="owner-name">Khanshmir etc.</text>
  </g>
  <g id="plot-13" class="plot-group">
    <title>Plot 13 - Owner: Sarmed/Zamad etc. (Reduced Width)</title>
    <path fill="#fff" stroke="#333" stroke-width="1.5" d="M367 280h123v80H367z"/>
    <text x="428.5" y="300" class="plot-number">125/13</text>
    <text x="428.5" y="320" class="owner-name">Sarmed/Zamad etc.</text>
  </g>
  <g id="plot-14" class="plot-group">
    <title>Plot 14 - Owner: Ilam Din/Qutab Din etc. (Adjusted Width)</title>
    <path fill="#fff" stroke="#333" stroke-width="1.5" d="M500 280h133v80H500z"/>
    <text x="566.5" y="300" class="plot-number">125/12</text>
    <text x="566.5" y="320" class="owner-name">Ilam Din/Qutab Din etc.</text>
  </g>
  <g id="plot-15" class="plot-group">
    <title>Plot 15 - Owner: Naved/Shafiq etc.</title>
    <path fill="#fff" stroke="#333" stroke-width="1.5" d="M633 280h133v80H633z"/>
    <text x="700" y="300" class="plot-number">125/11</text>
    <text x="700" y="320" class="owner-name">Naved/Shafiq etc.</text>
  </g>
  <g id="plot-16" class="plot-group">
    <title>Plot 16 - Subdivided: 16A (Naved/Shafiq etc.), 16B (Aish/Mushtaq etc.)</title>
    <path fill="#fff" stroke="#333" stroke-width="1.5" d="M766 280h134v80H766z"/>
    <path stroke="#666" stroke-dasharray="4,2" d="M766 320h134"/>
    <g id="plot-16A">
      <title>Plot 16A - Owner: Naved/Shafiq etc.</title>
      <text x="833" y="300" class="plot-number">124/15A</text>
      <text x="833" y="315" class="owner-name">Naved/Shafiq etc.</text>
    </g>
    <g id="plot-16B">
      <title>Plot 16B - Owner: Aish/Mushtaq etc.</title>
      <text x="833" y="340" class="plot-number">124/15B</text>
      <text x="833" y="355" class="owner-name">Aish/Mushtaq etc.</text>
    </g>
  </g>
  <g id="plot-21" class="plot-group">
    <title>Plot 21 - Owner: Khanshmir etc.</title>
    <path fill="#fff" stroke="#333" stroke-width="1.5" d="M100 360h133v80H100z"/>
    <text x="166.5" y="380" class="plot-number">125/6</text>
    <text x="166.5" y="400" class="owner-name">Khanshmir etc.</text>
  </g>
  <g id="plot-22" class="plot-group">
    <title>Plot 22 - Owner: Khanshmir etc.</title>
    <path fill="#fff" stroke="#333" stroke-width="1.5" d="M233 360h134v80H233z"/>
    <text x="300" y="380" class="plot-number">125/7</text>
    <text x="300" y="400" class="owner-name">Khanshmir etc.</text>
  </g>
  <g id="plot-23" class="plot-group">
    <title>Plot 23 - Owner: Sarmed/Zamad etc. (Reduced Width)</title>
    <path fill="#fff" stroke="#333" stroke-width="1.5" d="M367 360h123v80H367z"/>
    <text x="428.5" y="380" class="plot-number">125/8</text>
    <text x="428.5" y="400" class="owner-name">Sarmed/Zamad etc.</text>
  </g>
  <g id="plot-24" class="plot-group">
    <title>Plot 24 - Owner: Ilam Din/Qutab Din etc. (Adjusted Width)</title>
    <path fill="#fff" stroke="#333" stroke-width="1.5" d="M500 360h133v80H500z"/>
    <text x="566.5" y="380" class="plot-number">125/9</text>
    <text x="566.5" y="400" class="owner-name">Ilam Din/Qutab Din etc.</text>
  </g>
  <g id="plot-25" class="plot-group">
    <title>Plot 25 - Owner: Naved/Shafiq etc.</title>
    <path fill="#fff" stroke="#333" stroke-width="1.5" d="M633 360h133v80H633z"/>
    <text x="700" y="380" class="plot-number">125/10</text>
    <text x="700" y="400" class="owner-name">Naved/Shafiq etc.</text>
  </g>
  <g id="plot-26" class="plot-group">
    <title>Plot 26 - Owner: Aish/Mushtaq etc.</title>
    <path fill="#fff" stroke="#333" stroke-width="1.5" d="M766 360h134v80H766z"/>
    <text x="833" y="380" class="plot-number">124/6</text>
    <text x="833" y="400" class="owner-name">Aish/Mushtaq etc.</text>
  </g>
  <g id="plot-31" class="plot-group">
    <title>Plot 31 - Owner: Rana A. Sattar</title>
    <path class="irrelevant-plot-fill" stroke="#333" stroke-width="1.5" d="M100 440h133v80H100z"/>
    <text x="166.5" y="460" class="plot-number">125/5</text>
    <text x="166.5" y="480" class="owner-name">Rana A. Sattar</text>
    <text x="166.5" y="495" class="caption" font-size="9">(out of Khewat 202)</text>
  </g>
  <g id="plot-32" class="plot-group">
    <title>Plot 32 - Owner: Sarmed/Zamad etc.</title>
    <path fill="#fff" stroke="#333" stroke-width="1.5" d="M233 440h134v80H233z"/>
    <text x="300" y="460" class="plot-number">125/4</text>
    <text x="300" y="480" class="owner-name">Sarmed/Zamad etc.</text>
  </g>
  <g id="plot-33" class="plot-group">
    <title>Plot 33 - Owner: Sarmed/Zamad etc. (Reduced Width)</title>
    <path fill="#fff" stroke="#333" stroke-width="1.5" d="M367 440h123v80H367z"/>
    <text x="428.5" y="460" class="plot-number">125/3</text>
    <text x="428.5" y="480" class="owner-name">Sarmed/Zamad etc.</text>
  </g>
  <g id="plot-34" class="plot-group">
    <title>Plot 34 - Owner: Ilam Din/Qutab Din etc. (Adjusted Width)</title>
    <path fill="#fff" stroke="#333" stroke-width="1.5" d="M500 440h133v80H500z"/>
    <text x="566.5" y="460" class="plot-number">125/2</text>
    <text x="566.5" y="480" class="owner-name">Ilam Din/Qutab Din etc.</text>
  </g>
  <g id="plot-35" class="plot-group">
    <title>Plot 35 - Owner: Naved/Shafiq etc.</title>
    <path fill="#fff" stroke="#333" stroke-width="1.5" d="M633 440h133v80H633z"/>
    <text x="700" y="460" class="plot-number">125/1</text>
    <text x="700" y="480" class="owner-name">Naved/Shafiq etc.</text>
  </g>
  <g id="plot-36" class="plot-group">
    <title>Plot 36 - Owner: Shabbir Bhatti</title>
    <path class="irrelevant-plot-fill" stroke="#333" stroke-width="1.5" d="M766 440h134v80H766z"/>
    <text x="833" y="460" class="plot-number">124/5</text>
    <text x="833" y="480" class="owner-name">Shabbir Bhatti</text>
    <text x="833" y="495" class="caption" font-size="9">(out of Khewat 202)</text>
  </g>
  <g id="southern-drainage">
    <title>Southern Side Drainage Channel (Naali)</title>
    <path fill="url(#waterPattern)" stroke="#333" stroke-width="1.5" d="M100 520h820v20H100z"/>
    <path fill="rgba(173, 216, 230, 0.6)" stroke="#333" stroke-width="1.5" d="M100 520h820v20H100z"/>
  </g>
  <g id="western-drainage">
    <title>western Side Drainage Channel</title>
    <path fill="url(#waterPattern)" stroke="#333" stroke-width="1.5" d="M900-50h20v590h-20z"/>
    <path fill="rgba(173, 216, 230, 0.6)" stroke="#333" stroke-width="1.5" d="M900-50h20v590h-20z"/>
    <text x="900" y="330" class="common-area" transform="rotate(90 940 300)">western Drainage Channel</text>
  </g>
  <g id="bottom-compass-notes">
    <title>Compass and Notes Section</title>
    <g id="compass-rose">
      <circle cx="160" cy="567.5" r="20" fill="none" stroke="#333" stroke-width="1.5"/>
      <path stroke="#333" stroke-width="2" d="M160 547.5v40m-20-20h40"/>
      <path fill="#333" d="m160 587.5-5-10h10z"/>
      <text x="160" y="542" font-size="14" font-weight="700">S</text>
      <text x="160" y="597" font-size="12" font-weight="600">N</text>
      <text x="132" y="572" font-size="12" font-weight="600">E</text>
      <text x="188" y="572" font-size="12" font-weight="600">W</text>
    </g>
    <text class="caption" font-size="11" font-weight="700" id="notes-column"><tspan x="480" y="550">Note: Standard plot dimensions (220ft x 198ft) shown. Some widths/heights adjusted for passages.</tspan><tspan x="480" y="566">Subdivided plots have approximate dimensions. Common Passage Width: 11.5 ft.</tspan></text>
  </g>
</svg>
