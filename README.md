<?xml version="1.0" encoding="UTF-8"?>
<MyGUI type="Layout" version="3.2.0">
    <Widget type="Widget" skin="Ymss_Window6Skin" position="399 306 226 155" align="Center" layer="Modal" name="Root">
        <Widget type="Button" skin="Button" position="28 112 58 26" name="OkBtn">
            <Property key="Caption" value="确 定"/>
            <Property key="TextColour" value="1 0.941177 0.843137"/>
        </Widget>
        <Widget type="Button" skin="Button" position="137 112 58 26" name="CancelBtn">
            <Property key="Caption" value="取 消"/>
            <Property key="TextColour" value="1 0.941177 0.843137"/>
        </Widget>
        <Widget type="EditBox" skin="EditBox" position="17 86 63 20" name="priceGold">
            <Property key="TextAlign" value="Right Bottom"/>
            <Property key="TextColour" value="1 0.941177 0.843137"/>
            <Property key="Colour" value="1 1 1"/>
            <Property key="MaxTextLength" value="9"/>
            <Property key="Caption" value="999,999"/>
        </Widget>
        <Widget type="EditBox" skin="EditBox" position="105 86 28 20" name="priceSilver">
            <Property key="TextColour" value="1 0.941177 0.843137"/>
            <Property key="TextAlign" value="Right Bottom"/>
            <Property key="Colour" value="1 1 1"/>
            <Property key="MaxTextLength" value="3"/>
            <Property key="Caption" value="99"/>
        </Widget>
        <Widget type="Widget" skin="Ymss_Money2" position="133 89 24 18"/>
        <Widget type="EditBox" skin="EditBox" position="156 86 28 20" name="priceCopper">
            <Property key="TextAlign" value="Right Bottom"/>
            <Property key="TextColour" value="1 0.941177 0.843137"/>
            <Property key="Colour" value="1 1 1"/>
            <Property key="MaxTextLength" value="3"/>
            <Property key="Caption" value="99"/>
        </Widget>
        <Widget type="Widget" skin="Ymss_Money3" position="185 88 24 18"/>
        <Widget type="EditBox" skin="EditBox" position="91 38 40 20" name="saleItemCount">
            <Property key="TextAlign" value="Center"/>
            <Property key="TextColour" value="1 0.941177 0.843137"/>
            <Property key="Caption" value="99"/>
        </Widget>
        <Widget type="TextBox" skin="TextBox" position="37 38 53 20">
            <Property key="Caption" value="你要上架"/>
            <Property key="Colour" value="1 1 1"/>
            <Property key="TextColour" value="1 0.941177 0.843137"/>
            <Property key="TextAlign" value="Center"/>
        </Widget>
        <Widget type="TextBox" skin="TextBox" position="37 62 140 20">
            <Property key="Caption" value="请输入物品销售价格/件"/>
            <Property key="TextColour" value="1 0.941177 0.843137"/>
        </Widget>
        <Widget type="Widget" skin="Ymss_Money1" position="81 89 24 18"/>
        <Widget type="TextBox" skin="TextBox" position="132 39 60 20">
            <Property key="Caption" value="件该物品"/>
            <Property key="TextAlign" value="Center"/>
            <Property key="TextColour" value="1 0.941177 0.843137"/>
        </Widget>
        <Widget type="TextBox" skin="TextBox" position="70 4 86 18">
            <Property key="Caption" value="商品上架"/>
            <Property key="FontName" value="SimheiFont.12"/>
            <Property key="TextAlign" value="Center"/>
            <Property key="TextColour" value="1 0.941177 0.843137"/>
        </Widget>
    </Widget>
</MyGUI>
