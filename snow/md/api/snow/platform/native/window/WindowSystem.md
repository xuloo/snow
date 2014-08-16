
[![Logo](../../../../../images/logo.png)](../../../../../api/index.html)

---



<h1>WindowSystem</h1>
<small>`snow.platform.native.window.WindowSystem`</small>



---

`class`extends <code><span>snow.window.WindowSystemBinding</span></code>
<span class="meta">
<br/>meta: @:build(&#x27;???&#x27;), @:autoBuild(&#x27;???&#x27;), @:noCompletion
</span>


---

&nbsp;
&nbsp;



<h3>Members</h3> <hr/>





<h3>Methods</h3> <hr/><span class="method apipage">
            <a name="init"><a class="lift" href="#init">init</a></a> <div class="clear"></div><code class="signature apipage">init() : [Void](#)</code><br/><span class="small_desc_flat"></span>
        </span>
    <span class="method apipage">
            <a name="process"><a class="lift" href="#process">process</a></a> <div class="clear"></div><code class="signature apipage">process() : [Void](#)</code><br/><span class="small_desc_flat"></span>
        </span>
    <span class="method apipage">
            <a name="destroy"><a class="lift" href="#destroy">destroy</a></a> <div class="clear"></div><code class="signature apipage">destroy() : [Void](#)</code><br/><span class="small_desc_flat"></span>
        </span>
    <span class="method apipage">
            <a name="create"><a class="lift" href="#create">create</a></a> <div class="clear"></div><code class="signature apipage">create(config:[snow.types.WindowConfig](#)<span></span>, on\_created:[snow.types.WindowHandle](#)&nbsp; -&gt; [Int](#)&nbsp; -&gt; [snow.types.WindowConfig](#)&nbsp;-&gt; [Void](#)<span></span>) : [Void](#)</code><br/><span class="small_desc_flat"></span>
        </span>
    <span class="method apipage">
            <a name="close"><a class="lift" href="#close">close</a></a> <div class="clear"></div><code class="signature apipage">close(window:[snow.window.Window](#)<span></span>) : [Void](#)</code><br/><span class="small_desc_flat"></span>
        </span>
    <span class="method apipage">
            <a name="show"><a class="lift" href="#show">show</a></a> <div class="clear"></div><code class="signature apipage">show(window:[snow.window.Window](#)<span></span>) : [Void](#)</code><br/><span class="small_desc_flat"></span>
        </span>
    <span class="method apipage">
            <a name="destroy_window"><a class="lift" href="#destroy_window">destroy\_window</a></a> <div class="clear"></div><code class="signature apipage">destroy\_window(window:[snow.window.Window](#)<span></span>) : [Void](#)</code><br/><span class="small_desc_flat"></span>
        </span>
    <span class="method apipage">
            <a name="update"><a class="lift" href="#update">update</a></a> <div class="clear"></div><code class="signature apipage">update(window:[snow.window.Window](#)<span></span>) : [Void](#)</code><br/><span class="small_desc_flat"></span>
        </span>
    <span class="method apipage">
            <a name="render"><a class="lift" href="#render">render</a></a> <div class="clear"></div><code class="signature apipage">render(window:[snow.window.Window](#)<span></span>) : [Void](#)</code><br/><span class="small_desc_flat"></span>
        </span>
    <span class="method apipage">
            <a name="swap"><a class="lift" href="#swap">swap</a></a> <div class="clear"></div><code class="signature apipage">swap(window:[snow.window.Window](#)<span></span>) : [Void](#)</code><br/><span class="small_desc_flat"></span>
        </span>
    <span class="method apipage">
            <a name="simple_message"><a class="lift" href="#simple_message">simple\_message</a></a> <div class="clear"></div><code class="signature apipage">simple\_message(window:[snow.window.Window](#)<span></span>, message:[String](#)<span></span>, title:[String](#)<span>=&#x27;&#x27;</span>) : [Void](#)</code><br/><span class="small_desc_flat"></span>
        </span>
    <span class="method apipage">
            <a name="set_size"><a class="lift" href="#set_size">set\_size</a></a> <div class="clear"></div><code class="signature apipage">set\_size(window:[snow.window.Window](#)<span></span>, w:[Int](#)<span></span>, h:[Int](#)<span></span>) : [Void](#)</code><br/><span class="small_desc_flat"></span>
        </span>
    <span class="method apipage">
            <a name="set_position"><a class="lift" href="#set_position">set\_position</a></a> <div class="clear"></div><code class="signature apipage">set\_position(window:[snow.window.Window](#)<span></span>, x:[Int](#)<span></span>, y:[Int](#)<span></span>) : [Void](#)</code><br/><span class="small_desc_flat"></span>
        </span>
    <span class="method apipage">
            <a name="set_title"><a class="lift" href="#set_title">set\_title</a></a> <div class="clear"></div><code class="signature apipage">set\_title(window:[snow.window.Window](#)<span></span>, title:[String](#)<span></span>) : [Void](#)</code><br/><span class="small_desc_flat"></span>
        </span>
    <span class="method apipage">
            <a name="set_max_size"><a class="lift" href="#set_max_size">set\_max\_size</a></a> <div class="clear"></div><code class="signature apipage">set\_max\_size(window:[snow.window.Window](#)<span></span>, w:[Int](#)<span></span>, h:[Int](#)<span></span>) : [Void](#)</code><br/><span class="small_desc_flat"></span>
        </span>
    <span class="method apipage">
            <a name="set_min_size"><a class="lift" href="#set_min_size">set\_min\_size</a></a> <div class="clear"></div><code class="signature apipage">set\_min\_size(window:[snow.window.Window](#)<span></span>, w:[Int](#)<span></span>, h:[Int](#)<span></span>) : [Void](#)</code><br/><span class="small_desc_flat"></span>
        </span>
    <span class="method apipage">
            <a name="fullscreen"><a class="lift" href="#fullscreen">fullscreen</a></a> <div class="clear"></div><code class="signature apipage">fullscreen(window:[snow.window.Window](#)<span></span>, fullscreen:[Bool](#)<span></span>, fullscreen\_desktop:[Bool](#)<span>=true</span>) : [Void](#)</code><br/><span class="small_desc_flat"></span>
        </span>
    <span class="method apipage">
            <a name="bordered"><a class="lift" href="#bordered">bordered</a></a> <div class="clear"></div><code class="signature apipage">bordered(window:[snow.window.Window](#)<span></span>, bordered:[Bool](#)<span></span>) : [Void](#)</code><br/><span class="small_desc_flat"></span>
        </span>
    <span class="method apipage">
            <a name="grab"><a class="lift" href="#grab">grab</a></a> <div class="clear"></div><code class="signature apipage">grab(window:[snow.window.Window](#)<span></span>, grabbed:[Bool](#)<span></span>) : [Void](#)</code><br/><span class="small_desc_flat"></span>
        </span>
    <span class="method apipage">
            <a name="set_cursor_position"><a class="lift" href="#set_cursor_position">set\_cursor\_position</a></a> <div class="clear"></div><code class="signature apipage">set\_cursor\_position(window:[snow.window.Window](#)<span></span>, x:[Int](#)<span></span>, y:[Int](#)<span></span>) : [Void](#)</code><br/><span class="small_desc_flat"></span>
        </span>
    <span class="method apipage">
            <a name="system_lock_cursor"><a class="lift" href="#system_lock_cursor">system\_lock\_cursor</a></a> <div class="clear"></div><code class="signature apipage">system\_lock\_cursor(enable:[Bool](#)<span></span>) : [Void](#)</code><br/><span class="small_desc_flat">Lock the OS cursor to the foreground window. This hides the cursor and prevents it from leaving, reporting relative coordinates.</span>
        </span>
    <span class="method apipage">
            <a name="system_enable_cursor"><a class="lift" href="#system_enable_cursor">system\_enable\_cursor</a></a> <div class="clear"></div><code class="signature apipage">system\_enable\_cursor(enable:[Bool](#)<span></span>) : [Void](#)</code><br/><span class="small_desc_flat">Toggle the OS cursor. This is not window specific but system wide</span>
        </span>
    <span class="method apipage">
            <a name="system_enable_vsync"><a class="lift" href="#system_enable_vsync">system\_enable\_vsync</a></a> <div class="clear"></div><code class="signature apipage">system\_enable\_vsync(enable:[Bool](#)<span></span>) : [Int](#)</code><br/><span class="small_desc_flat">Toggle vertical refresh. This is not window specific but context wide</span>
        </span>
    <span class="method apipage">
            <a name="display_count"><a class="lift" href="#display_count">display\_count</a></a> <div class="clear"></div><code class="signature apipage">display\_count() : [Int](#)</code><br/><span class="small_desc_flat"></span>
        </span>
    <span class="method apipage">
            <a name="display_mode_count"><a class="lift" href="#display_mode_count">display\_mode\_count</a></a> <div class="clear"></div><code class="signature apipage">display\_mode\_count(display:[Int](#)<span></span>) : [Int](#)</code><br/><span class="small_desc_flat"></span>
        </span>
    <span class="method apipage">
            <a name="display_native_mode"><a class="lift" href="#display_native_mode">display\_native\_mode</a></a> <div class="clear"></div><code class="signature apipage">display\_native\_mode(display:[Int](#)<span></span>) : [snow.types.DisplayMode](#)</code><br/><span class="small_desc_flat"></span>
        </span>
    <span class="method apipage">
            <a name="display_current_mode"><a class="lift" href="#display_current_mode">display\_current\_mode</a></a> <div class="clear"></div><code class="signature apipage">display\_current\_mode(display:[Int](#)<span></span>) : [snow.types.DisplayMode](#)</code><br/><span class="small_desc_flat"></span>
        </span>
    <span class="method apipage">
            <a name="display_mode"><a class="lift" href="#display_mode">display\_mode</a></a> <div class="clear"></div><code class="signature apipage">display\_mode(display:[Int](#)<span></span>, mode\_index:[Int](#)<span></span>) : [snow.types.DisplayMode](#)</code><br/><span class="small_desc_flat"></span>
        </span>
    <span class="method apipage">
            <a name="display_bounds"><a class="lift" href="#display_bounds">display\_bounds</a></a> <div class="clear"></div><code class="signature apipage">display\_bounds(display:[Int](#)<span></span>) : [Dynamic](#)</code><br/><span class="small_desc_flat"></span>
        </span>
    <span class="method apipage">
            <a name="display_name"><a class="lift" href="#display_name">display\_name</a></a> <div class="clear"></div><code class="signature apipage">display\_name(display:[Int](#)<span></span>) : [String](#)</code><br/><span class="small_desc_flat"></span>
        </span>
    <span class="method apipage">
            <a name="new"><a class="lift" href="#new">new</a></a> <div class="clear"></div><code class="signature apipage">new(\_manager:[snow.window.Windowing](#)<span></span>, \_lib:[snow.Snow](#)<span></span>) : [Void](#)</code><br/><span class="small_desc_flat"></span>
        </span>
    





---

&nbsp;
&nbsp;
&nbsp;
&nbsp;