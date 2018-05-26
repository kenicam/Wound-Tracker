<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE MudletPackage>
<MudletPackage version="1.001">
    <TriggerPackage>
        <Trigger isActive="yes" isFolder="no" isTempTrigger="no" isMultiline="no" isPerlSlashGOption="no" isColorizerTrigger="no" isFilterTrigger="no" isSoundTrigger="no" isColorTrigger="no" isColorTriggerFg="no" isColorTriggerBg="no">
            <name>wound_tracker_start</name>
            <script>wound_tracker = {}
wound_colours = {
[&quot;no&quot;] = &quot;green&quot;,
[&quot;light&quot;] = &quot;yellow&quot;,
[&quot;heavy&quot;] = &quot;red&quot;,
[&quot;critical&quot;] = &quot;purple&quot;,

}</script>
            <triggerType>0</triggerType>
            <conditonLineDelta>0</conditonLineDelta>
            <mStayOpen>1000</mStayOpen>
            <mCommand></mCommand>
            <packageName></packageName>
            <mFgColor>#ff0000</mFgColor>
            <mBgColor>#ffff00</mBgColor>
            <mSoundFile></mSoundFile>
            <colorTriggerFgColor>#000000</colorTriggerFgColor>
            <colorTriggerBgColor>#000000</colorTriggerBgColor>
            <regexCodeList>
                <string>^You assess the bodily wounds as follows\:$</string>
            </regexCodeList>
            <regexCodePropertyList>
                <integer>1</integer>
            </regexCodePropertyList>
            <Trigger isActive="yes" isFolder="no" isTempTrigger="no" isMultiline="no" isPerlSlashGOption="no" isColorizerTrigger="no" isFilterTrigger="no" isSoundTrigger="no" isColorTrigger="no" isColorTriggerFg="no" isColorTriggerBg="no">
                <name>Head</name>
                <script>local t = wound_tracker

for k,v in pairs(wound_colours) do
if matches[2] == k then
t.h = {wounds = matches[2],  name = &quot;H&quot;, colour = v}
end
end 
</script>
                <triggerType>0</triggerType>
                <conditonLineDelta>0</conditonLineDelta>
                <mStayOpen>0</mStayOpen>
                <mCommand></mCommand>
                <packageName></packageName>
                <mFgColor>#ff0000</mFgColor>
                <mBgColor>#ffff00</mBgColor>
                <mSoundFile></mSoundFile>
                <colorTriggerFgColor>#000000</colorTriggerFgColor>
                <colorTriggerBgColor>#000000</colorTriggerBgColor>
                <regexCodeList>
                    <string>^\* Head has (\w+) wounds\.$</string>
                </regexCodeList>
                <regexCodePropertyList>
                    <integer>1</integer>
                </regexCodePropertyList>
            </Trigger>
            <Trigger isActive="yes" isFolder="no" isTempTrigger="no" isMultiline="no" isPerlSlashGOption="no" isColorizerTrigger="no" isFilterTrigger="no" isSoundTrigger="no" isColorTrigger="no" isColorTriggerFg="no" isColorTriggerBg="no">
                <name>Chest</name>
                <script>local t = wound_tracker
for k,v in pairs(wound_colours) do
if matches[2] == k then
t.c = {wounds = matches[2],  name = &quot;C&quot;, colour = v}
end
end </script>
                <triggerType>0</triggerType>
                <conditonLineDelta>0</conditonLineDelta>
                <mStayOpen>0</mStayOpen>
                <mCommand></mCommand>
                <packageName></packageName>
                <mFgColor>#ff0000</mFgColor>
                <mBgColor>#ffff00</mBgColor>
                <mSoundFile></mSoundFile>
                <colorTriggerFgColor>#000000</colorTriggerFgColor>
                <colorTriggerBgColor>#000000</colorTriggerBgColor>
                <regexCodeList>
                    <string>\* Chest has (\w+) wounds\.$</string>
                </regexCodeList>
                <regexCodePropertyList>
                    <integer>1</integer>
                </regexCodePropertyList>
            </Trigger>
            <Trigger isActive="yes" isFolder="no" isTempTrigger="no" isMultiline="no" isPerlSlashGOption="no" isColorizerTrigger="no" isFilterTrigger="no" isSoundTrigger="no" isColorTrigger="no" isColorTriggerFg="no" isColorTriggerBg="no">
                <name>Gut</name>
                <script>local t = wound_tracker
for k,v in pairs(wound_colours) do
if matches[2] == k then
t.g = {wounds = matches[2],  name = &quot;G&quot;, colour = v}
end
end </script>
                <triggerType>0</triggerType>
                <conditonLineDelta>0</conditonLineDelta>
                <mStayOpen>0</mStayOpen>
                <mCommand></mCommand>
                <packageName></packageName>
                <mFgColor>#ff0000</mFgColor>
                <mBgColor>#ffff00</mBgColor>
                <mSoundFile></mSoundFile>
                <colorTriggerFgColor>#000000</colorTriggerFgColor>
                <colorTriggerBgColor>#000000</colorTriggerBgColor>
                <regexCodeList>
                    <string>\* Gut has (\w+) wounds\.$</string>
                </regexCodeList>
                <regexCodePropertyList>
                    <integer>1</integer>
                </regexCodePropertyList>
            </Trigger>
            <Trigger isActive="yes" isFolder="no" isTempTrigger="no" isMultiline="no" isPerlSlashGOption="no" isColorizerTrigger="no" isFilterTrigger="no" isSoundTrigger="no" isColorTrigger="no" isColorTriggerFg="no" isColorTriggerBg="no">
                <name>Left arm</name>
                <script>local t = wound_tracker
for k,v in pairs(wound_colours) do
if matches[2] == k then
t.la = {wounds = matches[2],  name = &quot;LA&quot;, colour = v}
end
end </script>
                <triggerType>0</triggerType>
                <conditonLineDelta>0</conditonLineDelta>
                <mStayOpen>0</mStayOpen>
                <mCommand></mCommand>
                <packageName></packageName>
                <mFgColor>#ff0000</mFgColor>
                <mBgColor>#ffff00</mBgColor>
                <mSoundFile></mSoundFile>
                <colorTriggerFgColor>#000000</colorTriggerFgColor>
                <colorTriggerBgColor>#000000</colorTriggerBgColor>
                <regexCodeList>
                    <string>\* Left arm has (\w+) wounds\.$</string>
                </regexCodeList>
                <regexCodePropertyList>
                    <integer>1</integer>
                </regexCodePropertyList>
            </Trigger>
            <Trigger isActive="yes" isFolder="no" isTempTrigger="no" isMultiline="no" isPerlSlashGOption="no" isColorizerTrigger="no" isFilterTrigger="no" isSoundTrigger="no" isColorTrigger="no" isColorTriggerFg="no" isColorTriggerBg="no">
                <name>Right arm</name>
                <script>local t = wound_tracker
for k,v in pairs(wound_colours) do
if matches[2] == k then
t.ra = {wounds = matches[2],  name = &quot;RA&quot;, colour = v}
end
end </script>
                <triggerType>0</triggerType>
                <conditonLineDelta>0</conditonLineDelta>
                <mStayOpen>0</mStayOpen>
                <mCommand></mCommand>
                <packageName></packageName>
                <mFgColor>#ff0000</mFgColor>
                <mBgColor>#ffff00</mBgColor>
                <mSoundFile></mSoundFile>
                <colorTriggerFgColor>#000000</colorTriggerFgColor>
                <colorTriggerBgColor>#000000</colorTriggerBgColor>
                <regexCodeList>
                    <string>\* Right arm has (\w+) wounds\.$</string>
                </regexCodeList>
                <regexCodePropertyList>
                    <integer>1</integer>
                </regexCodePropertyList>
            </Trigger>
            <Trigger isActive="yes" isFolder="no" isTempTrigger="no" isMultiline="no" isPerlSlashGOption="no" isColorizerTrigger="no" isFilterTrigger="no" isSoundTrigger="no" isColorTrigger="no" isColorTriggerFg="no" isColorTriggerBg="no">
                <name>Left leg</name>
                <script>local t = wound_tracker
for k,v in pairs(wound_colours) do
if matches[2] == k then
t.ll = {wounds = matches[2],  name = &quot;LL&quot;, colour = v}
end
end </script>
                <triggerType>0</triggerType>
                <conditonLineDelta>0</conditonLineDelta>
                <mStayOpen>0</mStayOpen>
                <mCommand></mCommand>
                <packageName></packageName>
                <mFgColor>#ff0000</mFgColor>
                <mBgColor>#ffff00</mBgColor>
                <mSoundFile></mSoundFile>
                <colorTriggerFgColor>#000000</colorTriggerFgColor>
                <colorTriggerBgColor>#000000</colorTriggerBgColor>
                <regexCodeList>
                    <string>\* Left leg has (\w+) wounds\.$</string>
                </regexCodeList>
                <regexCodePropertyList>
                    <integer>1</integer>
                </regexCodePropertyList>
            </Trigger>
            <Trigger isActive="yes" isFolder="no" isTempTrigger="no" isMultiline="no" isPerlSlashGOption="no" isColorizerTrigger="no" isFilterTrigger="no" isSoundTrigger="no" isColorTrigger="no" isColorTriggerFg="no" isColorTriggerBg="no">
                <name>Right leg</name>
                <script>local t = wound_tracker
for k,v in pairs(wound_colours) do
if matches[2] == k then
t.rl = {wounds = matches[2],  name = &quot;RL&quot;, colour = v}
end
end </script>
                <triggerType>0</triggerType>
                <conditonLineDelta>0</conditonLineDelta>
                <mStayOpen>0</mStayOpen>
                <mCommand></mCommand>
                <packageName></packageName>
                <mFgColor>#ff0000</mFgColor>
                <mBgColor>#ffff00</mBgColor>
                <mSoundFile></mSoundFile>
                <colorTriggerFgColor>#000000</colorTriggerFgColor>
                <colorTriggerBgColor>#000000</colorTriggerBgColor>
                <regexCodeList>
                    <string>\* Right leg has (\w+) wounds\.$</string>
                </regexCodeList>
                <regexCodePropertyList>
                    <integer>1</integer>
                </regexCodePropertyList>
            </Trigger>
            <Trigger isActive="yes" isFolder="no" isTempTrigger="no" isMultiline="no" isPerlSlashGOption="no" isColorizerTrigger="no" isFilterTrigger="no" isSoundTrigger="no" isColorTrigger="no" isColorTriggerFg="no" isColorTriggerBg="no">
                <name>Close Gate</name>
                <script>setTriggerStayOpen(&quot;wound_tracker_start&quot;, 0)
local t = wound_tracker
cecho(&quot;&lt;&quot;..t.h.colour ..&quot;&gt;[&quot;..t.h.name ..&quot;] &quot;)
cecho(&quot;&lt;&quot;..t.c.colour ..&quot;&gt;[&quot;..t.c.name ..&quot;] &quot;)
cecho(&quot;&lt;&quot;..t.g.colour ..&quot;&gt;[&quot;..t.g.name ..&quot;] &quot;)
cecho(&quot;&lt;&quot;..t.la.colour ..&quot;&gt;[&quot;..t.la.name ..&quot;] &quot;)
cecho(&quot;&lt;&quot;..t.ra.colour ..&quot;&gt;[&quot;..t.ra.name ..&quot;] &quot;)
cecho(&quot;&lt;&quot;..t.ll.colour ..&quot;&gt;[&quot;..t.ll.name ..&quot;] &quot;)
cecho(&quot;&lt;&quot;..t.rl.colour ..&quot;&gt;[&quot;..t.rl.name ..&quot;] &quot;)
cecho(&quot;\n &quot;)

wound_update()
wound_container:show()</script>
                <triggerType>0</triggerType>
                <conditonLineDelta>0</conditonLineDelta>
                <mStayOpen>0</mStayOpen>
                <mCommand></mCommand>
                <packageName></packageName>
                <mFgColor>#ff0000</mFgColor>
                <mBgColor>#ffff00</mBgColor>
                <mSoundFile></mSoundFile>
                <colorTriggerFgColor>#000000</colorTriggerFgColor>
                <colorTriggerBgColor>#000000</colorTriggerBgColor>
                <regexCodeList>
                    <string>return isPrompt()</string>
                </regexCodeList>
                <regexCodePropertyList>
                    <integer>4</integer>
                </regexCodePropertyList>
            </Trigger>
        </Trigger>
    </TriggerPackage>
    <TimerPackage>
        <Timer isActive="no" isFolder="no" isTempTimer="no" isOffsetTimer="no">
            <name>wound_resize_window</name>
            <script>local x, y = getMousePosition()
wound_new_width = windowpositions.wound_width + (x - windowpositions.wound_start_x)
wound_new_height = windowpositions.wound_height + (y - windowpositions.wound_start_y)

wound_container:resize(wound_new_width, wound_new_height)</script>
            <command></command>
            <packageName></packageName>
            <time>00:00:00.000</time>
        </Timer>
        <Timer isActive="no" isFolder="no" isTempTimer="no" isOffsetTimer="no">
            <name>wound_drag_window</name>
            <script>local x, y = getMousePosition()
windowpositions.wound_x = x
windowpositions.wound_y = y
table.save(getMudletHomeDir() .. &quot;/windowpositions&quot;, windowpositions)
wound_container:move(getMousePosition())</script>
            <command></command>
            <packageName></packageName>
            <time>00:00:00.000</time>
        </Timer>
    </TimerPackage>
    <AliasPackage/>
    <ActionPackage/>
    <ScriptPackage>
        <Script isActive="yes" isFolder="no">
            <name>file_exists</name>
            <packageName></packageName>
            <script>function file_exists(name)
   local f=io.open(name,&quot;r&quot;)
   if f~=nil then io.close(f) return true else return false end
end</script>
            <eventHandlerList/>
        </Script>
        <Script isActive="yes" isFolder="no">
            <name>main</name>
            <packageName></packageName>
            <script>

windowpositions = {
	wound_x = 50,
	wound_y = 50,

	wound_width = 400,
	wound_height = 300,

	wound_start_x = nil,
	wound_start_y = nil,
}


if file_exists(getMudletHomeDir()..&quot;/windowpositions&quot;) then
table.load(getMudletHomeDir() .. &quot;/windowpositions&quot;, windowpositions)
end

local background_color = &quot;rgb(153, 179, 255)&quot;
local title_color = &quot;rgb(0 , 85, 128)&quot;
local border_color = &quot;rgb(122, 122, 82)&quot;
local button_color = &quot;rgb(27, 30, 35)&quot;
local text_color = &quot;white&quot;  --this one has to be a word, until I can figure out how to do it differently

--[[ 
https://www.w3schools.com/colors/colors_picker.asp
--]]

wound_container = Geyser.Container:new({
	name = &quot;wound_container&quot;,
	x = windowpositions.wound_x, y = windowpositions.wound_y,
	width = windowpositions.wound_width,
	height = windowpositions.wound_height,	
})

wound_background_label = Geyser.Label:new({
	name = &quot;wound_background_label&quot;,
	x = 0, y = 0,
	width = &quot;100%&quot;,
	height = &quot;100%&quot;,
	
}, wound_container)
wound_background_label:setStyleSheet([[
	background-color: ]]..background_color..[[;
]])

wound_title_bar = Geyser.Label:new({
	name = &quot;wound_title_bar&quot;,
	x = &quot;5%&quot;, y = 0,
	width = &quot;95%&quot;,
	height = &quot;8%&quot;,
	fgColor = text_color,
	message = [[&lt;center&gt;Wound Window&lt;/center&gt;]]
}, wound_container)
wound_title_bar:setStyleSheet([[
	background-color: ]]..title_color..[[;
]])

wound_drag_move = Geyser.Label:new({
	name = &quot;wound_drag_move&quot;,
	x = 0, y = 0,
	width = &quot;5%&quot;,
	height = &quot;8%&quot;,
	fgColor = text_color,
	message = [[&lt;center&gt;+&lt;/center&gt;]]
}, wound_container)
wound_drag_move:setStyleSheet([[
	background-color: ]]..title_color..[[;
]])
wound_hide = Geyser.Label:new({
	name = &quot;wound_hide&quot;,
	x = &quot;95%&quot;, y = 0,
	width = &quot;5%&quot;,
	height = &quot;8%&quot;,
	fgColor = text_color,
	message = [[&lt;center&gt;X&lt;/center&gt;]]
}, wound_container)
wound_hide:setStyleSheet([[
	background-color: ]]..title_color..[[;
]])
function woundhide()
wound_container:hide()
end
wound_hide:setClickCallback(&quot;woundhide&quot;)


wound_hbox1 = Geyser.HBox:new({
	name = &quot;wound_hbox1&quot;,
	x = 0, y = &quot;8%&quot;,
	width = &quot;100%&quot;,
	height = &quot;23%&quot;,
}, wound_container)

wound_head = Geyser.Label:new({
	name = &quot;wound_head&quot;,
	fgColor = text_color,
	message = [[&lt;center&gt;Head&lt;/center&gt;]]
	
}, wound_hbox1)
wound_head:setStyleSheet([[
	background-color: ]]..button_color..[[;
  border-width: 1px;
  border-style: solid;
  border-color: ]]..border_color..[[;
  border-radius: 2px;
]])

wound_hbox2 = Geyser.HBox:new({
	name = &quot;wound_hbox2&quot;,
	x = 0, y = &quot;31%&quot;,
	width = &quot;100%&quot;,
	height = &quot;23%&quot;,
}, wound_container)

wound_chest = Geyser.Label:new({
	name = &quot;wound_chest&quot;,
	fgColor = text_color,
	message = [[&lt;center&gt;Chest&lt;/center&gt;]]
	
}, wound_hbox2)
wound_chest:setStyleSheet([[
	background-color: ]]..button_color..[[;
  border-width: 1px;
  border-style: solid;
  border-color: ]]..border_color..[[;
  border-radius: 2px;
]])

wound_gut = Geyser.Label:new({
	name = &quot;wound_gut&quot;,
	fgColor = text_color,
	message = [[&lt;center&gt;Gut&lt;/center&gt;]]
	
}, wound_hbox2)
wound_gut:setStyleSheet([[
	background-color: ]]..button_color..[[;
  border-width: 1px;
  border-style: solid;
  border-color: ]]..border_color..[[;
  border-radius: 2px;
]])

wound_hbox3 = Geyser.HBox:new({
	name = &quot;wound_hbox3&quot;,
	x = 0, y = &quot;54%&quot;,
	width = &quot;100%&quot;,
	height = &quot;23%&quot;,
}, wound_container)

wound_leftarm = Geyser.Label:new({
	name = &quot;wound_leftarm&quot;,
	fgColor = text_color,
	message = [[&lt;center&gt;Left Arm&lt;/center&gt;]]
	
}, wound_hbox3)
wound_leftarm:setStyleSheet([[
	background-color: ]]..button_color..[[;
  border-width: 1px;
  border-style: solid;
  border-color: ]]..border_color..[[;
  border-radius: 2px;
]])

wound_rightarm = Geyser.Label:new({
	name = &quot;wound_rightarm&quot;,
	fgColor = text_color,
	message = [[&lt;center&gt;Right Arm&lt;/center&gt;]]
	
}, wound_hbox3)
wound_rightarm:setStyleSheet([[
	background-color: ]]..button_color..[[;
  border-width: 1px;
  border-style: solid;
  border-color: ]]..border_color..[[;
  border-radius: 2px;
]])

wound_hbox4 = Geyser.HBox:new({
	name = &quot;wound_hbox4&quot;,
	x = 0, y = &quot;77%&quot;,
	width = &quot;100%&quot;,
	height = &quot;23%&quot;,
}, wound_container)

wound_leftleg = Geyser.Label:new({
	name = &quot;wound_leftleg&quot;,
	fgColor = text_color,
	message = [[&lt;center&gt;Left Leg&lt;/center&gt;]]
	
}, wound_hbox4)
wound_leftleg:setStyleSheet([[
	background-color: ]]..button_color..[[;
  border-width: 1px;
  border-style: solid;
  border-color: ]]..border_color..[[;
  border-radius: 2px;
]])

wound_rightleg = Geyser.Label:new({
	name = &quot;wound_rightleg&quot;,
	fgColor = text_color,
	message = [[&lt;center&gt;Right Leg&lt;/center&gt;]]
	
}, wound_hbox4)
wound_rightleg:setStyleSheet([[
	background-color: ]]..button_color..[[;
  border-width: 1px;
  border-style: solid;
  border-color: ]]..border_color..[[;
  border-radius: 2px;
]])

wound_resize_label = Geyser.Label:new({
	x = &quot;95%&quot;, y = &quot;95%&quot;,
	width = &quot;5%&quot;,
	height = &quot;5%&quot;,
	message = [[&lt;center&gt;*&lt;/center&gt;]]
}, wound_container)
wound_resize_label:setStyleSheet([[
	background-color: rgba(0,0,0,0%);
]])
function wound_drag_click()
enableTimer(&quot;wound_drag_window&quot;)
end
function wound_drag_release()
disableTimer(&quot;wound_drag_window&quot;)
end
function wound_resize_click()
windowpositions.wound_start_x, windowpositions.wound_start_y = getMousePosition()
enableTimer(&quot;wound_resize_window&quot;)
end
function wound_resize_release()
disableTimer(&quot;wound_resize_window&quot;)
windowpositions.wound_width = wound_new_width
windowpositions.wound_height = wound_new_height
table.save(getMudletHomeDir() .. &quot;/windowpositions&quot;, windowpositions)
end
wound_resize_label:setClickCallback(&quot;wound_resize_click&quot;)
wound_resize_label:setReleaseCallback(&quot;wound_resize_release&quot;)
wound_drag_move:setClickCallback(&quot;wound_drag_click&quot;)
wound_drag_move:setReleaseCallback(&quot;wound_drag_release&quot;)
wound_container:show()</script>
            <eventHandlerList/>
        </Script>
        <Script isActive="yes" isFolder="no">
            <name>update</name>
            <packageName></packageName>
            <script>function wound_update()
head_color = wound_tracker.h.colour
chest_color = wound_tracker.c.colour
gut_color = wound_tracker.g.colour
leftarm_color = wound_tracker.la.colour
rightarm_color = wound_tracker.ra.colour
leftleg_color = wound_tracker.ll.colour
rightleg_color = wound_tracker.rl.colour

local border_color = &quot;rgb(122, 122, 82)&quot;
wound_head:setStyleSheet([[
	background-color: ]]..head_color..[[;
  border-width: 1px;
  border-style: solid;
  border-color: ]]..border_color..[[;
  border-radius: 2px;
]])

wound_chest:setStyleSheet([[
	background-color: ]]..chest_color..[[;
  border-width: 1px;
  border-style: solid;
  border-color: ]]..border_color..[[;
  border-radius: 2px;
]])

wound_gut:setStyleSheet([[
	background-color: ]]..gut_color..[[;
  border-width: 1px;
  border-style: solid;
  border-color: ]]..border_color..[[;
  border-radius: 2px;
]])

wound_leftarm:setStyleSheet([[
	background-color: ]]..leftarm_color..[[;
  border-width: 1px;
  border-style: solid;
  border-color: ]]..border_color..[[;
  border-radius: 2px;
]])


wound_rightarm:setStyleSheet([[
	background-color: ]]..rightarm_color..[[;
  border-width: 1px;
  border-style: solid;
  border-color: ]]..border_color..[[;
  border-radius: 2px;
]])

wound_leftleg:setStyleSheet([[
	background-color: ]]..leftleg_color..[[;
  border-width: 1px;
  border-style: solid;
  border-color: ]]..border_color..[[;
  border-radius: 2px;
]])

wound_rightleg:setStyleSheet([[
	background-color: ]]..rightleg_color..[[;
  border-width: 1px;
  border-style: solid;
  border-color: ]]..border_color..[[;
  border-radius: 2px;
]])
end</script>
            <eventHandlerList/>
        </Script>
    </ScriptPackage>
    <KeyPackage/>
</MudletPackage>
