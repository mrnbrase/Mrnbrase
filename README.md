# Mrnbrase

<Widget type="TabControl" skin="TabControl" position="640 249 196 32" name="tabControl">
                <Property key="ButtonWidth" value="79"/>
                <Property key="SmoothShow" value="false"/>
                <Widget type="TabItem" skin="" position="0 30 196 -11">
                    <Property key="Caption" value="NPC"/>
                </Widget>
                <Widget type="TabItem" skin="" position="0 30 196 -11">
                    <Property key="Caption" value="怪物"/>
                </Widget>
            </Widget>
            <Widget type="MultiListBox" skin="Ymss_MultiListBox" position="644 280 187 375" name="npcList"/>
            <Widget type="MultiListBox" skin="Ymss_MultiListBox" position="644 280 186 375" name="monsterList"/>
            <Widget type="TextBox" skin="TextBox" position="648 306 173 23" name="seeknpcerror">
                <Property key="TextColour" value="1 0 0"/>
                <Property key="Caption" value="当前地图没有该NPC/怪物"/>
                <Property key="TextAlign" value="Center"/>
                <Property key="Visible" value="false"/>
            </Widget>
            <Widget type="TextBox" skin="TextBox" position="643 222 126 25" name="Seektips">
                <Property key="TextColour" value="0.517647 0.388235 0.278431"/>
                <Property key="Caption" value="搜索NPC/怪物"/>
                <Property key="TextAlign" value="Left VCenter"/>
                <Property key="NeedMouse" value="false"/>
            </Widget>
            <Widget type="ImageBox" skin="Ymss_Ornamental1" position="640 57 205 13"/>
            <Widget type="ImageBox" skin="Ymss_Ornamental1" position="638 98 204 11"/>
            <Widget type="ImageBox" skin="Ymss_Ornamental1" position="636 181 207 4"/>
            <Widget type="ImageBox" skin="Ymss_Ornamental1" position="637 213 206 10"/>
            <Widget type="ImageBox" skin="Ymss_EditBoxSkin" position="641 281 192 374">
                <Property key="NeedMouse" value="false"/>
            </Widget>
        </Widget>
    </Resource>
    <Resource type="ResourceLayout" name="Bigmap_MarkDialog.layout" version="3.2.0">
        <Widget type="Widget" skin="PanelEmpty" position="234 264 348 244" layer="Modal" name="_Main">
            <Widget type="Widget" skin="Ymss_Window8Skin" position="0 0 314 222">
                <Widget type="Widget" skin="PanelEmpty" position="8 42 298 172">
                    <Widget type="TextBox" skin="TextBox" position="20 13 33 17">
                        <Property key="Caption" value="名称"/>
                        <Property key="TextColour" value="0.941177 0.960784 0.466667"/>
                    </Widget>
                    <Widget type="EditBox" skin="EditBox" position="55 13 156 20" name="text_name">
                        <Property key="MaxTextLength" value="12"/>
                    </Widget>
                    <Widget type="TextBox" skin="TextBox" position="20 43 33 17">
                        <Property key="Caption" value="描述"/>
                        <Property key="TextColour" value="0.960784 0.941177 0.466667"/>
                    </Widget>
                    <Widget type="EditBox" skin="EditBox" position="55 43 156 20" name="text_description">
                        <Property key="MaxTextLength" value="25"/>
                    </Widget>
                    <Widget type="TextBox" skin="TextBox" position="20 73 33 17">
                        <Property key="Caption" value="标记"/>
                        <Property key="TextColour" value="0.960784 0.941177 0.466667"/>
                    </Widget>
                    <Widget type="TextBox" skin="TextBox" position="20 105 73 17">
                        <Property key="Caption" value="发送给玩家："/>
                        <Property key="TextColour" value="0.960784 0.941177 0.466667"/>
                    </Widget>
                    <Widget type="EditBox" skin="EditBox" position="100 104 122 20" name="text_playerto"/>
                    <Widget type="Button" skin="Button" position="226 100 58 26" name="btn_send">
                        <Property key="Caption" value="发送"/>
                        <Property key="FontName" value="Default"/>
                        <Property key="TextAlign" value="HCenter Top"/>
                        <Property key="TextColour" value="1 1 1"/>
                        <Property key="TextShadowColour" value="0 0 0"/>
                        <Property key="TextShadow" value="true"/>
                    </Widget>
                    <Widget type="Button" skin="Button" position="60 140 58 26" name="btn_ok">
                        <Property key="Caption" value="确认"/>
                        <Property key="FontName" value="Default"/>
                        <Property key="TextAlign" value="HCenter Top"/>
                        <Property key="TextColour" value="1 1 1"/>
                    </Widget>
                    <Widget type="Button" skin="Button" position="165 140 58 26" name="btn_cancel">
                        <Property key="Caption" value="取消"/>
                        <Property key="TextAlign" value="HCenter Top"/>
                        <Property key="FontName" value="Default"/>
                        <Property key="TextColour" value="1 1 1"/>
                    </Widget>
                    <Widget type="Button" skin="ditubiaoji_biaoji1" position="55 72 25 25" name="icon_0"/>
                    <Widget type="Button" skin="ditubiaoji_biaoji2" position="82 72 25 25" name="icon_1"/>
                    <Widget type="Button" skin="ditubiaoji_biaoji3" position="109 72 25 25" name="icon_2"/>
                    <Widget type="Button" skin="ditubiaoji_biaoji4" position="136 72 25 25" name="icon_3"/>
                    <Widget type="Button" skin="ditubiaoji_biaoji5" position="163 72 25 25" name="icon_4"/>
                    <Widget type="Button" skin="ditubiaoji_biaoji6" position="190 72 25 25" name="icon_5"/>
                    <Widget type="Button" skin="ditubiaoji_biaoji7" position="217 72 25 25" name="icon_6"/>
                    <Widget type="TextBox" skin="TextBox" position="62 13 142 20" name="text_name_default">
                        <Property key="Alpha" value="0.8"/>
                        <Property key="TextColour" value="0.784314 0.784314 0.784314"/>
                        <Property key="Caption" value="新标记2"/>
                        <Property key="NeedKey" value="false"/>
                        <Property key="NeedMouse" value="false"/>
                        <Property key="NeedToolTip" value="false"/>
                        <Property key="TextAlign" value="Left Bottom"/>
                    </Widget>
                </Widget>
                <Widget type="TextBox" skin="TextBox" position="52 1 210 26" name="text_caption">
                    <Property key="Caption" value="编辑标记"/>
                    <Property key="TextAlign" value="Center"/>
                    <Property key="FontName" value="SimheiFont.16"/>
                    <Property key="TextShadow" value="true"/>
                    <Property key="TextShadowColour" value="0 0 0"/>
                    <Property key="TextColour" value="1 0.941177 0.843137"/>
                </Widget>
                <Widget type="Button" skin="ButtonCloseSkin" position="289 21 20 20" name="markClose"/>
            </Widget>
        </Widget>
    </Resource>
    <Resource type="ResourceLayout" name="Bigmap_MapImage.layout" version="3.2.0">
        <Widget type="Widget" skin="PanelEmpty" position="0 0 600 600" layer="Main" name="_Main">
            <Widget type="ImageBox" skin="ImageBox" position="93 79 500 500" align="Default" name="imagebox_map">
                <Widget type="ImageBox" skin="ImageBox" position="237 233 23 26" name="Clicked">
                    <Property key="NeedMouse" value="false"/>
                </Widget>
                <Widget type="ImageBox" skin="ImageBox" position="248 277 16 16" name="Mousedest"/>
            </Widget>
        </Widget>
    </Resource>
    <Resource type="ResourceLayout" name="Bigmap_MiniMap.layout" version="3.2.0">
        <Widget type="ImageBox" skin="ImageBox" position="700 42 200 200" layer="Info" name="_Main"/>
    </Resource>
    <Resource type="ResourceLayout" name="Bigmap_MarkToolTip.layout" version="3.2.0">
        <Widget type="Widget" skin="Ymss_TipsWindowSkin" position="68 38 207 188" layer="ToolTip" name="_Main">
            <Widget type="EditBox" skin="TextBox" position="18 7 163 21" name="text_markName">
                <Property key="TextAlign" value="Center"/>
                <Property key="MaxTextLength" value="12"/>
            </Widget>
            <Widget type="TextBox" skin="TextBox" position="18 30 50 25">
                <Property key="Caption" value="区域："/>
            </Widget>
            <Widget type="TextBox" skin="TextBox" position="18 65 50 25">
                <Property key="Caption" value="位置："/>
            </Widget>
            <Widget type="TextBox" skin="TextBox" position="18 100 50 25">
                <Property key="Caption" value="距离："/>
            </Widget>
            <Widget type="TextBox" skin="TextBox" position="18 135 50 25">
                <Property key="Caption" value="描述："/>
            </Widget>
            <Widget type="TextBox" skin="TextBox" position="75 30 120 25" name="text_area">
                <Property key="TextAlign" value="Right Top"/>
            </Widget>
            <Widget type="TextBox" skin="TextBox" position="75 65 120 25" name="text_position">
                <Property key="TextAlign" value="Right Top"/>
            </Widget>
            <Widget type="TextBox" skin="TextBox" position="75 100 120 25" name="text_distance">
                <Property key="TextAlign" value="Right Top"/>
            </Widget>
            <Widget type="EditBox" skin="WordWrapEmpty" position="68 135 133 47" name="text_description">
                <Property key="TextAlign" value="Left Top"/>
                <Property key="NeedMouse" value="false"/>
                <Property key="NeedKey" value="false"/>
                <Property key="MultiLine" value="true"/>
                <Property key="ReadOnly" value="true"/>
                <Property key="WordWrap" value="true"/>
                <Property key="Static" value="true"/>
                <Property key="VisibleHScroll" value="false"/>
                <Property key="VisibleVScroll" value="false"/>
            </Widget>
        </Widget>
    </Resource>
    <Resource type="ResourceLayout" name="Bigmap_CloseButton.layout" version="3.2.0">
        <Widget type="Button" skin="ditubiaoji_shanchusuoyoubiaoji" position="944 28 32 32" layer="Main" name="_Main"/>
    </Resource>
</MyGUI>
