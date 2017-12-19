# packageJson-for-create-react-app

This is an enhanced package.json file.

copy dependencies and scripts.


<div style="background: #272822; overflow:auto;width:auto;border:solid gray;border-width:.1em .1em .1em .8em;padding:.2em .6em;"><pre style="margin: 0; line-height: 125%">   <span style="color: #e6db74">&quot;dependencies&quot;</span><span style="color: #f92672">:</span> <span style="color: #f8f8f2">{</span>
    <span style="color: #e6db74">&quot;babel-polyfill&quot;</span><span style="color: #f92672">:</span> <span style="color: #e6db74">&quot;^6.26.0&quot;</span><span style="color: #f8f8f2">,</span>
    <span style="color: #e6db74">&quot;classnames&quot;</span><span style="color: #f92672">:</span> <span style="color: #e6db74">&quot;^2.2.5&quot;</span><span style="color: #f8f8f2">,</span>
    <span style="color: #e6db74">&quot;eslint&quot;</span><span style="color: #f92672">:</span> <span style="color: #e6db74">&quot;^4.12.0&quot;</span><span style="color: #f8f8f2">,</span>
    <span style="color: #e6db74">&quot;node-sass-chokidar&quot;</span><span style="color: #f92672">:</span> <span style="color: #e6db74">&quot;^0.0.3&quot;</span><span style="color: #f8f8f2">,</span>
    <span style="color: #e6db74">&quot;npm-run-all&quot;</span><span style="color: #f92672">:</span> <span style="color: #e6db74">&quot;^4.1.1&quot;</span><span style="color: #f8f8f2">,</span>
    <span style="color: #e6db74">&quot;react&quot;</span><span style="color: #f92672">:</span> <span style="color: #e6db74">&quot;^16.0.0&quot;</span><span style="color: #f8f8f2">,</span>
    <span style="color: #e6db74">&quot;react-dom&quot;</span><span style="color: #f92672">:</span> <span style="color: #e6db74">&quot;^16.0.0&quot;</span><span style="color: #f8f8f2">,</span>
    <span style="color: #e6db74">&quot;react-font-icon&quot;</span><span style="color: #f92672">:</span> <span style="color: #e6db74">&quot;^1.0.0&quot;</span><span style="color: #f8f8f2">,</span>
    <span style="color: #e6db74">&quot;react-icons&quot;</span><span style="color: #f92672">:</span> <span style="color: #e6db74">&quot;^2.2.7&quot;</span><span style="color: #f8f8f2">,</span>
    <span style="color: #e6db74">&quot;react-router-dom&quot;</span><span style="color: #f92672">:</span> <span style="color: #e6db74">&quot;^4.2.2&quot;</span><span style="color: #f8f8f2">,</span>
    <span style="color: #e6db74">&quot;react-scripts&quot;</span><span style="color: #f92672">:</span> <span style="color: #e6db74">&quot;1.0.14&quot;</span>
  <span style="color: #f8f8f2">},</span>
  <span style="color: #e6db74">&quot;scripts&quot;</span><span style="color: #f92672">:</span> <span style="color: #f8f8f2">{</span>
    <span style="color: #e6db74">&quot;build-css&quot;</span><span style="color: #f92672">:</span> <span style="color: #e6db74">&quot;node-sass-chokidar src/ -o src/&quot;</span><span style="color: #f8f8f2">,</span>
    <span style="color: #e6db74">&quot;watch-css&quot;</span><span style="color: #f92672">:</span> <span style="color: #e6db74">&quot;npm run build-css &amp;&amp; node-sass-chokidar src/ -o src/ --watch --recursive&quot;</span><span style="color: #f8f8f2">,</span>
    <span style="color: #e6db74">&quot;start-js&quot;</span><span style="color: #f92672">:</span> <span style="color: #e6db74">&quot;react-scripts start&quot;</span><span style="color: #f8f8f2">,</span>
    <span style="color: #e6db74">&quot;start&quot;</span><span style="color: #f92672">:</span> <span style="color: #e6db74">&quot;npm-run-all -p watch-css start-js&quot;</span><span style="color: #f8f8f2">,</span>
    <span style="color: #e6db74">&quot;build&quot;</span><span style="color: #f92672">:</span> <span style="color: #e6db74">&quot;npm run build-css &amp;&amp; react-scripts build&quot;</span><span style="color: #f8f8f2">,</span>
    <span style="color: #e6db74">&quot;test&quot;</span><span style="color: #f92672">:</span> <span style="color: #e6db74">&quot;react-scripts test --env=jsdom&quot;</span><span style="color: #f8f8f2">,</span>
    <span style="color: #e6db74">&quot;eject&quot;</span><span style="color: #f92672">:</span> <span style="color: #e6db74">&quot;react-scripts eject&quot;</span>
  <span style="color: #f8f8f2">}</span>
</pre></div>

