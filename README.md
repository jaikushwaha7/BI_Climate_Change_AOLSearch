# BI_Climate_Change_AOLSearch
Breif Summary, discussion and data

**How to Use This Data**

1. MOnthly atmospheric data
2. Sea level Monthly
3. Daily world temperature

### MOre data to come

**Sample Task questions that can be answered by our data**

1. How aware were the people about the climate, pollution and environment in 2006
   1.1 Were exactly the were searching
   1.2 Which countries daily search count, average daily and monthly rollup

2. Were people searching daily temperature
   2.1 If they were checking what was the average temperature and which site or domain was most search
   

Schema:


<mxfile host="app.diagrams.net" agent="Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/129.0.0.0 Safari/537.36 Edg/129.0.0.0" version="24.8.4">
  <diagram name="Page-1" id="QS1cl5HhRHRCwGJWDw4-">
    <mxGraphModel dx="1221" dy="739" grid="1" gridSize="10" guides="1" tooltips="1" connect="1" arrows="1" fold="1" page="1" pageScale="1" pageWidth="827" pageHeight="1169" math="0" shadow="0">
      <root>
        <mxCell id="0" />
        <mxCell id="1" parent="0" />
        <mxCell id="25B0M3Xmif-6wFpoJRKW-1" value="TIMEDIM" style="swimlane;fontStyle=0;childLayout=stackLayout;horizontal=1;startSize=26;fillColor=#0050ef;horizontalStack=0;resizeParent=1;resizeParentMax=0;resizeLast=0;collapsible=1;marginBottom=0;html=1;strokeColor=#001DBC;gradientDirection=radial;swimlaneFillColor=none;rounded=0;shadow=1;glass=0;fontColor=#ffffff;align=center;labelBackgroundColor=none;fontFamily=Verdana;" parent="1" vertex="1">
          <mxGeometry x="260" y="80" width="140" height="174" as="geometry" />
        </mxCell>
        <mxCell id="25B0M3Xmif-6wFpoJRKW-120" style="edgeStyle=none;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;fontFamily=Helvetica;fontSize=12;fontColor=#ffffff;fontStyle=0;" parent="25B0M3Xmif-6wFpoJRKW-1" edge="1">
          <mxGeometry relative="1" as="geometry">
            <mxPoint x="410" y="699.9999999999998" as="targetPoint" />
            <mxPoint x="140" y="39" as="sourcePoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="25B0M3Xmif-6wFpoJRKW-3" value="ID" style="text;strokeColor=none;fillColor=none;align=center;verticalAlign=top;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;whiteSpace=wrap;html=1;fontFamily=Verdana;" parent="25B0M3Xmif-6wFpoJRKW-1" vertex="1">
          <mxGeometry y="26" width="140" height="26" as="geometry" />
        </mxCell>
        <mxCell id="25B0M3Xmif-6wFpoJRKW-2" value="YEAR" style="text;strokeColor=none;fillColor=none;align=center;verticalAlign=middle;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;whiteSpace=wrap;html=1;fontFamily=Verdana;" parent="25B0M3Xmif-6wFpoJRKW-1" vertex="1">
          <mxGeometry y="52" width="140" height="26" as="geometry" />
        </mxCell>
        <mxCell id="25B0M3Xmif-6wFpoJRKW-4" value="MONTH" style="text;strokeColor=none;fillColor=none;align=center;verticalAlign=top;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;whiteSpace=wrap;html=1;fontFamily=Verdana;" parent="25B0M3Xmif-6wFpoJRKW-1" vertex="1">
          <mxGeometry y="78" width="140" height="32" as="geometry" />
        </mxCell>
        <mxCell id="25B0M3Xmif-6wFpoJRKW-51" value="DATE" style="text;strokeColor=none;fillColor=none;align=center;verticalAlign=top;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;whiteSpace=wrap;html=1;fontFamily=Verdana;" parent="25B0M3Xmif-6wFpoJRKW-1" vertex="1">
          <mxGeometry y="110" width="140" height="32" as="geometry" />
        </mxCell>
        <mxCell id="25B0M3Xmif-6wFpoJRKW-52" style="text;strokeColor=none;fillColor=none;align=left;verticalAlign=top;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;whiteSpace=wrap;html=1;fontFamily=Verdana;" parent="25B0M3Xmif-6wFpoJRKW-1" vertex="1">
          <mxGeometry y="142" width="140" height="32" as="geometry" />
        </mxCell>
        <mxCell id="25B0M3Xmif-6wFpoJRKW-42" value="FACTS" style="swimlane;fontStyle=0;childLayout=stackLayout;horizontal=1;startSize=26;fillColor=#0050ef;horizontalStack=0;resizeParent=1;resizeParentMax=0;resizeLast=0;collapsible=1;marginBottom=0;html=1;strokeColor=#001DBC;gradientDirection=radial;swimlaneFillColor=none;rounded=0;shadow=1;glass=0;fontColor=#ffffff;align=center;labelBackgroundColor=none;fontFamily=Verdana;" parent="1" vertex="1">
          <mxGeometry x="70" y="80" width="140" height="206" as="geometry">
            <mxRectangle x="78" y="121" width="80" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="25B0M3Xmif-6wFpoJRKW-43" value="ANONID" style="text;strokeColor=none;fillColor=none;align=center;verticalAlign=top;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;whiteSpace=wrap;html=1;fontFamily=Verdana;" parent="25B0M3Xmif-6wFpoJRKW-42" vertex="1">
          <mxGeometry y="26" width="140" height="26" as="geometry" />
        </mxCell>
        <mxCell id="25B0M3Xmif-6wFpoJRKW-44" value="QUERYID" style="text;strokeColor=none;fillColor=none;align=center;verticalAlign=middle;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;whiteSpace=wrap;html=1;fontFamily=Verdana;" parent="25B0M3Xmif-6wFpoJRKW-42" vertex="1">
          <mxGeometry y="52" width="140" height="26" as="geometry" />
        </mxCell>
        <mxCell id="25B0M3Xmif-6wFpoJRKW-45" value="TIMEID" style="text;strokeColor=none;fillColor=none;align=center;verticalAlign=top;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;whiteSpace=wrap;html=1;fontFamily=Verdana;" parent="25B0M3Xmif-6wFpoJRKW-42" vertex="1">
          <mxGeometry y="78" width="140" height="32" as="geometry" />
        </mxCell>
        <mxCell id="25B0M3Xmif-6wFpoJRKW-46" value="URLID" style="text;strokeColor=none;fillColor=none;align=center;verticalAlign=top;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;whiteSpace=wrap;html=1;fontFamily=Verdana;" parent="25B0M3Xmif-6wFpoJRKW-42" vertex="1">
          <mxGeometry y="110" width="140" height="32" as="geometry" />
        </mxCell>
        <mxCell id="25B0M3Xmif-6wFpoJRKW-47" value="IRANK" style="text;strokeColor=none;fillColor=none;align=center;verticalAlign=top;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;whiteSpace=wrap;html=1;fontFamily=Verdana;" parent="25B0M3Xmif-6wFpoJRKW-42" vertex="1">
          <mxGeometry y="142" width="140" height="32" as="geometry" />
        </mxCell>
        <mxCell id="25B0M3Xmif-6wFpoJRKW-50" value="CLICK" style="text;strokeColor=none;fillColor=none;align=center;verticalAlign=top;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;whiteSpace=wrap;html=1;fontFamily=Verdana;" parent="25B0M3Xmif-6wFpoJRKW-42" vertex="1">
          <mxGeometry y="174" width="140" height="32" as="geometry" />
        </mxCell>
        <mxCell id="25B0M3Xmif-6wFpoJRKW-53" value="ANONDIM" style="swimlane;fontStyle=0;childLayout=stackLayout;horizontal=1;startSize=26;fillColor=#0050ef;horizontalStack=0;resizeParent=1;resizeParentMax=0;resizeLast=0;collapsible=1;marginBottom=0;html=1;strokeColor=#001DBC;gradientDirection=radial;swimlaneFillColor=none;rounded=0;shadow=1;glass=0;fontColor=#ffffff;align=center;labelBackgroundColor=none;fontFamily=Verdana;" parent="1" vertex="1">
          <mxGeometry x="100" y="360" width="140" height="78" as="geometry" />
        </mxCell>
        <mxCell id="25B0M3Xmif-6wFpoJRKW-54" value="ANONID" style="text;strokeColor=none;fillColor=none;align=center;verticalAlign=top;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;whiteSpace=wrap;html=1;fontFamily=Verdana;" parent="25B0M3Xmif-6wFpoJRKW-53" vertex="1">
          <mxGeometry y="26" width="140" height="26" as="geometry" />
        </mxCell>
        <mxCell id="25B0M3Xmif-6wFpoJRKW-55" value="ID" style="text;strokeColor=none;fillColor=none;align=center;verticalAlign=middle;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;whiteSpace=wrap;html=1;fontFamily=Verdana;" parent="25B0M3Xmif-6wFpoJRKW-53" vertex="1">
          <mxGeometry y="52" width="140" height="26" as="geometry" />
        </mxCell>
        <mxCell id="25B0M3Xmif-6wFpoJRKW-59" value="QUERYDIM" style="swimlane;fontStyle=0;childLayout=stackLayout;horizontal=1;startSize=26;fillColor=#0050ef;horizontalStack=0;resizeParent=1;resizeParentMax=0;resizeLast=0;collapsible=1;marginBottom=0;html=1;strokeColor=#001DBC;gradientDirection=radial;swimlaneFillColor=none;rounded=0;shadow=1;glass=0;fontColor=#ffffff;align=center;labelBackgroundColor=none;fontFamily=Verdana;" parent="1" vertex="1">
          <mxGeometry x="100" y="500" width="140" height="78" as="geometry" />
        </mxCell>
        <mxCell id="25B0M3Xmif-6wFpoJRKW-60" value="QUERY" style="text;strokeColor=none;fillColor=none;align=center;verticalAlign=top;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;whiteSpace=wrap;html=1;fontFamily=Verdana;" parent="25B0M3Xmif-6wFpoJRKW-59" vertex="1">
          <mxGeometry y="26" width="140" height="26" as="geometry" />
        </mxCell>
        <mxCell id="25B0M3Xmif-6wFpoJRKW-61" value="ID" style="text;strokeColor=none;fillColor=none;align=center;verticalAlign=middle;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;whiteSpace=wrap;html=1;fontFamily=Verdana;" parent="25B0M3Xmif-6wFpoJRKW-59" vertex="1">
          <mxGeometry y="52" width="140" height="26" as="geometry" />
        </mxCell>
        <mxCell id="25B0M3Xmif-6wFpoJRKW-62" value="URLDIM" style="swimlane;fontStyle=0;childLayout=stackLayout;horizontal=1;startSize=30;fillColor=#0050ef;horizontalStack=0;resizeParent=1;resizeParentMax=0;resizeLast=0;collapsible=1;marginBottom=0;html=1;strokeColor=#001DBC;gradientDirection=radial;swimlaneFillColor=none;rounded=0;shadow=1;glass=0;fontColor=#ffffff;align=center;labelBackgroundColor=none;fontFamily=Verdana;" parent="1" vertex="1">
          <mxGeometry x="274" y="280" width="136" height="294" as="geometry">
            <mxRectangle x="78" y="121" width="80" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="25B0M3Xmif-6wFpoJRKW-63" value="URL" style="text;strokeColor=none;fillColor=none;align=center;verticalAlign=top;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;whiteSpace=wrap;html=1;fontFamily=Verdana;" parent="25B0M3Xmif-6wFpoJRKW-62" vertex="1">
          <mxGeometry y="30" width="136" height="26" as="geometry" />
        </mxCell>
        <mxCell id="25B0M3Xmif-6wFpoJRKW-64" value="ID" style="text;strokeColor=none;fillColor=none;align=center;verticalAlign=middle;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;whiteSpace=wrap;html=1;fontFamily=Verdana;" parent="25B0M3Xmif-6wFpoJRKW-62" vertex="1">
          <mxGeometry y="56" width="136" height="28" as="geometry" />
        </mxCell>
        <mxCell id="25B0M3Xmif-6wFpoJRKW-65" value="TITLE" style="text;strokeColor=none;fillColor=none;align=center;verticalAlign=top;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;whiteSpace=wrap;html=1;fontFamily=Verdana;" parent="25B0M3Xmif-6wFpoJRKW-62" vertex="1">
          <mxGeometry y="84" width="136" height="30" as="geometry" />
        </mxCell>
        <mxCell id="25B0M3Xmif-6wFpoJRKW-66" value="DSCRIPTION" style="text;strokeColor=none;fillColor=none;align=center;verticalAlign=top;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;whiteSpace=wrap;html=1;fontFamily=Verdana;" parent="25B0M3Xmif-6wFpoJRKW-62" vertex="1">
          <mxGeometry y="114" width="136" height="32" as="geometry" />
        </mxCell>
        <mxCell id="25B0M3Xmif-6wFpoJRKW-67" value="PROTOCOL" style="text;strokeColor=none;fillColor=none;align=center;verticalAlign=top;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;whiteSpace=wrap;html=1;fontFamily=Verdana;" parent="25B0M3Xmif-6wFpoJRKW-62" vertex="1">
          <mxGeometry y="146" width="136" height="32" as="geometry" />
        </mxCell>
        <mxCell id="25B0M3Xmif-6wFpoJRKW-68" value="&lt;p style=&quot;line-height: normal; margin-top: 0pt; margin-bottom: 0pt; margin-left: 0in; direction: ltr; unicode-bidi: embed; word-break: normal;&quot;&gt;&lt;font&gt;&lt;span style=&quot;font-size: 11px; letter-spacing: -0.01pt; background-color: initial;&quot;&gt;SUBDOMAIN&lt;/span&gt;&lt;br&gt;&lt;span style=&quot;font-size: 11px;&quot;&gt;&lt;br&gt;&lt;/span&gt;&lt;span style=&quot;font-size: 11px; letter-spacing: -0.01pt; background-color: initial;&quot;&gt;THISDOMAIN&lt;/span&gt;&lt;br&gt;&lt;span style=&quot;font-size: 11px;&quot;&gt;&lt;br&gt;&lt;/span&gt;&lt;span style=&quot;font-size: 11px; letter-spacing: -0.01pt; background-color: initial;&quot;&gt;TOPLEVELDOMAIN&lt;/span&gt;&lt;br&gt;&lt;span style=&quot;font-size: 11px;&quot;&gt;&lt;br&gt;&lt;/span&gt;&lt;span style=&quot;font-size: 11px; letter-spacing: -0.01pt; background-color: initial;&quot;&gt;THISPATH&lt;/span&gt;&lt;/font&gt;&lt;br&gt;&lt;/p&gt;" style="text;strokeColor=none;fillColor=none;align=center;verticalAlign=top;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;whiteSpace=wrap;html=1;fontFamily=Verdana;" parent="25B0M3Xmif-6wFpoJRKW-62" vertex="1">
          <mxGeometry y="178" width="136" height="116" as="geometry" />
        </mxCell>
        <mxCell id="25B0M3Xmif-6wFpoJRKW-72" value="URL CATEGORY" style="swimlane;fontStyle=0;childLayout=stackLayout;horizontal=1;startSize=26;fillColor=#0050ef;horizontalStack=0;resizeParent=1;resizeParentMax=0;resizeLast=0;collapsible=1;marginBottom=0;html=1;strokeColor=#001DBC;gradientDirection=radial;swimlaneFillColor=none;rounded=0;shadow=1;glass=0;fontColor=#ffffff;align=center;labelBackgroundColor=none;fontFamily=Verdana;" parent="1" vertex="1">
          <mxGeometry x="500" y="90" width="140" height="78" as="geometry" />
        </mxCell>
        <mxCell id="25B0M3Xmif-6wFpoJRKW-73" value="URLID" style="text;strokeColor=none;fillColor=none;align=center;verticalAlign=top;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;whiteSpace=wrap;html=1;fontFamily=Verdana;" parent="25B0M3Xmif-6wFpoJRKW-72" vertex="1">
          <mxGeometry y="26" width="140" height="26" as="geometry" />
        </mxCell>
        <mxCell id="25B0M3Xmif-6wFpoJRKW-74" value="CATEGORYID" style="text;strokeColor=none;fillColor=none;align=center;verticalAlign=middle;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;whiteSpace=wrap;html=1;fontFamily=Verdana;" parent="25B0M3Xmif-6wFpoJRKW-72" vertex="1">
          <mxGeometry y="52" width="140" height="26" as="geometry" />
        </mxCell>
        <mxCell id="25B0M3Xmif-6wFpoJRKW-76" value="DMOZ CATEGORY" style="swimlane;fontStyle=0;childLayout=stackLayout;horizontal=1;startSize=26;fillColor=#0050ef;horizontalStack=0;resizeParent=1;resizeParentMax=0;resizeLast=0;collapsible=1;marginBottom=0;html=1;strokeColor=#001DBC;gradientDirection=radial;swimlaneFillColor=none;rounded=0;shadow=1;glass=0;fontColor=#ffffff;align=center;labelBackgroundColor=none;fontFamily=Verdana;" parent="1" vertex="1">
          <mxGeometry x="450" y="286" width="140" height="174" as="geometry" />
        </mxCell>
        <mxCell id="25B0M3Xmif-6wFpoJRKW-78" value="CATID" style="text;strokeColor=none;fillColor=none;align=center;verticalAlign=middle;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;whiteSpace=wrap;html=1;fontFamily=Verdana;" parent="25B0M3Xmif-6wFpoJRKW-76" vertex="1">
          <mxGeometry y="26" width="140" height="26" as="geometry" />
        </mxCell>
        <mxCell id="25B0M3Xmif-6wFpoJRKW-77" value="TITLE" style="text;strokeColor=none;fillColor=none;align=center;verticalAlign=top;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;whiteSpace=wrap;html=1;fontFamily=Verdana;" parent="25B0M3Xmif-6wFpoJRKW-76" vertex="1">
          <mxGeometry y="52" width="140" height="26" as="geometry" />
        </mxCell>
        <mxCell id="25B0M3Xmif-6wFpoJRKW-79" value="DESICTION" style="text;strokeColor=none;fillColor=none;align=center;verticalAlign=top;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;whiteSpace=wrap;html=1;fontFamily=Verdana;" parent="25B0M3Xmif-6wFpoJRKW-76" vertex="1">
          <mxGeometry y="78" width="140" height="32" as="geometry" />
        </mxCell>
        <mxCell id="25B0M3Xmif-6wFpoJRKW-80" value="DATE" style="text;strokeColor=none;fillColor=none;align=center;verticalAlign=top;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;whiteSpace=wrap;html=1;fontFamily=Verdana;" parent="25B0M3Xmif-6wFpoJRKW-76" vertex="1">
          <mxGeometry y="110" width="140" height="32" as="geometry" />
        </mxCell>
        <mxCell id="25B0M3Xmif-6wFpoJRKW-81" style="text;strokeColor=none;fillColor=none;align=left;verticalAlign=top;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;whiteSpace=wrap;html=1;fontFamily=Verdana;" parent="25B0M3Xmif-6wFpoJRKW-76" vertex="1">
          <mxGeometry y="142" width="140" height="32" as="geometry" />
        </mxCell>
        <mxCell id="25B0M3Xmif-6wFpoJRKW-83" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;exitX=1;exitY=0.5;exitDx=0;exitDy=0;entryX=0;entryY=0.5;entryDx=0;entryDy=0;fontFamily=Helvetica;fontSize=12;fontColor=#ffffff;fontStyle=0;curved=1;" parent="1" source="25B0M3Xmif-6wFpoJRKW-45" target="25B0M3Xmif-6wFpoJRKW-3" edge="1">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="25B0M3Xmif-6wFpoJRKW-84" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;exitX=1;exitY=0.5;exitDx=0;exitDy=0;entryX=0;entryY=0.5;entryDx=0;entryDy=0;fontFamily=Helvetica;fontSize=12;fontColor=#ffffff;fontStyle=0;curved=1;" parent="1" source="25B0M3Xmif-6wFpoJRKW-46" target="25B0M3Xmif-6wFpoJRKW-64" edge="1">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="25B0M3Xmif-6wFpoJRKW-85" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;exitX=0;exitY=0.5;exitDx=0;exitDy=0;entryX=0;entryY=0.5;entryDx=0;entryDy=0;fontFamily=Helvetica;fontSize=12;fontColor=#ffffff;fontStyle=0;curved=1;" parent="1" source="25B0M3Xmif-6wFpoJRKW-43" target="25B0M3Xmif-6wFpoJRKW-54" edge="1">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="25B0M3Xmif-6wFpoJRKW-86" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;exitX=0;exitY=0.5;exitDx=0;exitDy=0;entryX=0;entryY=0.5;entryDx=0;entryDy=0;fontFamily=Helvetica;fontSize=12;fontColor=#ffffff;fontStyle=0;curved=1;" parent="1" source="25B0M3Xmif-6wFpoJRKW-44" target="25B0M3Xmif-6wFpoJRKW-61" edge="1">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="25B0M3Xmif-6wFpoJRKW-87" value="Daily Temperature" style="swimlane;fontStyle=0;childLayout=stackLayout;horizontal=1;startSize=26;fillColor=#0050ef;horizontalStack=0;resizeParent=1;resizeParentMax=0;resizeLast=0;collapsible=1;marginBottom=0;html=1;strokeColor=#001DBC;gradientDirection=radial;swimlaneFillColor=none;rounded=0;shadow=1;glass=0;fontColor=#ffffff;align=center;labelBackgroundColor=none;fontFamily=Verdana;" parent="1" vertex="1">
          <mxGeometry x="530" y="730" width="140" height="142" as="geometry" />
        </mxCell>
        <mxCell id="25B0M3Xmif-6wFpoJRKW-88" value="DateID" style="text;strokeColor=none;fillColor=none;align=center;verticalAlign=middle;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;whiteSpace=wrap;html=1;fontFamily=Verdana;" parent="25B0M3Xmif-6wFpoJRKW-87" vertex="1">
          <mxGeometry y="26" width="140" height="26" as="geometry" />
        </mxCell>
        <mxCell id="25B0M3Xmif-6wFpoJRKW-89" value="Date" style="text;strokeColor=none;fillColor=none;align=center;verticalAlign=top;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;whiteSpace=wrap;html=1;fontFamily=Verdana;" parent="25B0M3Xmif-6wFpoJRKW-87" vertex="1">
          <mxGeometry y="52" width="140" height="26" as="geometry" />
        </mxCell>
        <mxCell id="25B0M3Xmif-6wFpoJRKW-90" value="Temperature" style="text;strokeColor=none;fillColor=none;align=center;verticalAlign=top;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;whiteSpace=wrap;html=1;fontFamily=Verdana;" parent="25B0M3Xmif-6wFpoJRKW-87" vertex="1">
          <mxGeometry y="78" width="140" height="32" as="geometry" />
        </mxCell>
        <mxCell id="25B0M3Xmif-6wFpoJRKW-92" style="text;strokeColor=none;fillColor=none;align=left;verticalAlign=top;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;whiteSpace=wrap;html=1;fontFamily=Verdana;" parent="25B0M3Xmif-6wFpoJRKW-87" vertex="1">
          <mxGeometry y="110" width="140" height="32" as="geometry" />
        </mxCell>
        <mxCell id="25B0M3Xmif-6wFpoJRKW-93" value="Sea Level" style="swimlane;fontStyle=0;childLayout=stackLayout;horizontal=1;startSize=26;fillColor=#0050ef;horizontalStack=0;resizeParent=1;resizeParentMax=0;resizeLast=0;collapsible=1;marginBottom=0;html=1;strokeColor=#001DBC;gradientDirection=radial;swimlaneFillColor=none;rounded=0;shadow=1;glass=0;fontColor=#ffffff;align=center;labelBackgroundColor=none;fontFamily=Verdana;" parent="1" vertex="1">
          <mxGeometry x="320" y="750" width="140" height="174" as="geometry" />
        </mxCell>
        <mxCell id="25B0M3Xmif-6wFpoJRKW-94" value="Date" style="text;strokeColor=none;fillColor=none;align=center;verticalAlign=middle;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;whiteSpace=wrap;html=1;fontFamily=Verdana;" parent="25B0M3Xmif-6wFpoJRKW-93" vertex="1">
          <mxGeometry y="26" width="140" height="26" as="geometry" />
        </mxCell>
        <mxCell id="25B0M3Xmif-6wFpoJRKW-121" style="edgeStyle=none;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;exitX=1;exitY=0.5;exitDx=0;exitDy=0;fontFamily=Helvetica;fontSize=12;fontColor=#ffffff;fontStyle=0;" parent="25B0M3Xmif-6wFpoJRKW-93" source="25B0M3Xmif-6wFpoJRKW-95" edge="1">
          <mxGeometry relative="1" as="geometry">
            <mxPoint x="80" y="-630" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="25B0M3Xmif-6wFpoJRKW-95" value="DateID" style="text;strokeColor=none;fillColor=none;align=center;verticalAlign=top;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;whiteSpace=wrap;html=1;fontFamily=Verdana;" parent="25B0M3Xmif-6wFpoJRKW-93" vertex="1">
          <mxGeometry y="52" width="140" height="26" as="geometry" />
        </mxCell>
        <mxCell id="25B0M3Xmif-6wFpoJRKW-96" value="SeaLevel" style="text;strokeColor=none;fillColor=none;align=center;verticalAlign=top;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;whiteSpace=wrap;html=1;fontFamily=Verdana;" parent="25B0M3Xmif-6wFpoJRKW-93" vertex="1">
          <mxGeometry y="78" width="140" height="32" as="geometry" />
        </mxCell>
        <mxCell id="25B0M3Xmif-6wFpoJRKW-97" value="DATE" style="text;strokeColor=none;fillColor=none;align=center;verticalAlign=top;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;whiteSpace=wrap;html=1;fontFamily=Verdana;" parent="25B0M3Xmif-6wFpoJRKW-93" vertex="1">
          <mxGeometry y="110" width="140" height="32" as="geometry" />
        </mxCell>
        <mxCell id="25B0M3Xmif-6wFpoJRKW-98" style="text;strokeColor=none;fillColor=none;align=left;verticalAlign=top;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;whiteSpace=wrap;html=1;fontFamily=Verdana;" parent="25B0M3Xmif-6wFpoJRKW-93" vertex="1">
          <mxGeometry y="142" width="140" height="32" as="geometry" />
        </mxCell>
        <mxCell id="25B0M3Xmif-6wFpoJRKW-99" value="CO2 Level" style="swimlane;fontStyle=0;childLayout=stackLayout;horizontal=1;startSize=26;fillColor=#0050ef;horizontalStack=0;resizeParent=1;resizeParentMax=0;resizeLast=0;collapsible=1;marginBottom=0;html=1;strokeColor=#001DBC;gradientDirection=radial;swimlaneFillColor=none;rounded=0;shadow=1;glass=0;fontColor=#ffffff;align=center;labelBackgroundColor=none;fontFamily=Verdana;" parent="1" vertex="1">
          <mxGeometry x="60" y="750" width="140" height="174" as="geometry" />
        </mxCell>
        <mxCell id="25B0M3Xmif-6wFpoJRKW-100" value="Date" style="text;strokeColor=none;fillColor=none;align=center;verticalAlign=middle;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;whiteSpace=wrap;html=1;fontFamily=Verdana;" parent="25B0M3Xmif-6wFpoJRKW-99" vertex="1">
          <mxGeometry y="26" width="140" height="26" as="geometry" />
        </mxCell>
        <mxCell id="25B0M3Xmif-6wFpoJRKW-101" value="DateID" style="text;strokeColor=none;fillColor=none;align=center;verticalAlign=top;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;whiteSpace=wrap;html=1;fontFamily=Verdana;" parent="25B0M3Xmif-6wFpoJRKW-99" vertex="1">
          <mxGeometry y="52" width="140" height="26" as="geometry" />
        </mxCell>
        <mxCell id="25B0M3Xmif-6wFpoJRKW-102" value="Co2LEVEL" style="text;strokeColor=none;fillColor=none;align=center;verticalAlign=top;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;whiteSpace=wrap;html=1;fontFamily=Verdana;" parent="25B0M3Xmif-6wFpoJRKW-99" vertex="1">
          <mxGeometry y="78" width="140" height="32" as="geometry" />
        </mxCell>
        <mxCell id="25B0M3Xmif-6wFpoJRKW-103" value="DATE" style="text;strokeColor=none;fillColor=none;align=center;verticalAlign=top;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;whiteSpace=wrap;html=1;fontFamily=Verdana;" parent="25B0M3Xmif-6wFpoJRKW-99" vertex="1">
          <mxGeometry y="110" width="140" height="32" as="geometry" />
        </mxCell>
        <mxCell id="25B0M3Xmif-6wFpoJRKW-104" style="text;strokeColor=none;fillColor=none;align=left;verticalAlign=top;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;whiteSpace=wrap;html=1;fontFamily=Verdana;" parent="25B0M3Xmif-6wFpoJRKW-99" vertex="1">
          <mxGeometry y="142" width="140" height="32" as="geometry" />
        </mxCell>
        <mxCell id="25B0M3Xmif-6wFpoJRKW-106" value="TemperatureCIty" style="swimlane;fontStyle=0;childLayout=stackLayout;horizontal=1;startSize=26;fillColor=#0050ef;horizontalStack=0;resizeParent=1;resizeParentMax=0;resizeLast=0;collapsible=1;marginBottom=0;html=1;strokeColor=#001DBC;gradientDirection=radial;swimlaneFillColor=none;rounded=0;shadow=1;glass=0;fontColor=#ffffff;align=center;labelBackgroundColor=none;fontFamily=Verdana;" parent="1" vertex="1">
          <mxGeometry x="510" y="940" width="140" height="142" as="geometry" />
        </mxCell>
        <mxCell id="25B0M3Xmif-6wFpoJRKW-107" value="Temperature" style="text;strokeColor=none;fillColor=none;align=center;verticalAlign=middle;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;whiteSpace=wrap;html=1;fontFamily=Verdana;" parent="25B0M3Xmif-6wFpoJRKW-106" vertex="1">
          <mxGeometry y="26" width="140" height="26" as="geometry" />
        </mxCell>
        <mxCell id="25B0M3Xmif-6wFpoJRKW-108" value="LocationID" style="text;strokeColor=none;fillColor=none;align=center;verticalAlign=top;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;whiteSpace=wrap;html=1;fontFamily=Verdana;" parent="25B0M3Xmif-6wFpoJRKW-106" vertex="1">
          <mxGeometry y="52" width="140" height="26" as="geometry" />
        </mxCell>
        <mxCell id="25B0M3Xmif-6wFpoJRKW-109" value="DateId" style="text;strokeColor=none;fillColor=none;align=center;verticalAlign=top;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;whiteSpace=wrap;html=1;fontFamily=Verdana;" parent="25B0M3Xmif-6wFpoJRKW-106" vertex="1">
          <mxGeometry y="78" width="140" height="32" as="geometry" />
        </mxCell>
        <mxCell id="25B0M3Xmif-6wFpoJRKW-110" style="text;strokeColor=none;fillColor=none;align=left;verticalAlign=top;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;whiteSpace=wrap;html=1;fontFamily=Verdana;" parent="25B0M3Xmif-6wFpoJRKW-106" vertex="1">
          <mxGeometry y="110" width="140" height="32" as="geometry" />
        </mxCell>
        <mxCell id="25B0M3Xmif-6wFpoJRKW-111" value="Location" style="swimlane;fontStyle=0;childLayout=stackLayout;horizontal=1;startSize=26;fillColor=#0050ef;horizontalStack=0;resizeParent=1;resizeParentMax=0;resizeLast=0;collapsible=1;marginBottom=0;html=1;strokeColor=#001DBC;gradientDirection=radial;swimlaneFillColor=none;rounded=0;shadow=1;glass=0;fontColor=#ffffff;align=center;labelBackgroundColor=none;fontFamily=Verdana;" parent="1" vertex="1">
          <mxGeometry x="230" y="970" width="140" height="174" as="geometry" />
        </mxCell>
        <mxCell id="25B0M3Xmif-6wFpoJRKW-112" value="LocationID" style="text;strokeColor=none;fillColor=none;align=center;verticalAlign=middle;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;whiteSpace=wrap;html=1;fontFamily=Verdana;" parent="25B0M3Xmif-6wFpoJRKW-111" vertex="1">
          <mxGeometry y="26" width="140" height="26" as="geometry" />
        </mxCell>
        <mxCell id="25B0M3Xmif-6wFpoJRKW-113" value="Country" style="text;strokeColor=none;fillColor=none;align=center;verticalAlign=top;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;whiteSpace=wrap;html=1;fontFamily=Verdana;" parent="25B0M3Xmif-6wFpoJRKW-111" vertex="1">
          <mxGeometry y="52" width="140" height="26" as="geometry" />
        </mxCell>
        <mxCell id="25B0M3Xmif-6wFpoJRKW-114" value="Continent" style="text;strokeColor=none;fillColor=none;align=center;verticalAlign=top;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;whiteSpace=wrap;html=1;fontFamily=Verdana;" parent="25B0M3Xmif-6wFpoJRKW-111" vertex="1">
          <mxGeometry y="78" width="140" height="32" as="geometry" />
        </mxCell>
        <mxCell id="25B0M3Xmif-6wFpoJRKW-115" value="Longitute" style="text;strokeColor=none;fillColor=none;align=center;verticalAlign=top;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;whiteSpace=wrap;html=1;fontFamily=Verdana;" parent="25B0M3Xmif-6wFpoJRKW-111" vertex="1">
          <mxGeometry y="110" width="140" height="32" as="geometry" />
        </mxCell>
        <mxCell id="25B0M3Xmif-6wFpoJRKW-117" value="Latitude" style="text;strokeColor=none;fillColor=none;align=center;verticalAlign=top;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;whiteSpace=wrap;html=1;fontFamily=Verdana;" parent="25B0M3Xmif-6wFpoJRKW-111" vertex="1">
          <mxGeometry y="142" width="140" height="32" as="geometry" />
        </mxCell>
        <mxCell id="25B0M3Xmif-6wFpoJRKW-118" style="edgeStyle=none;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;exitX=1;exitY=0.5;exitDx=0;exitDy=0;entryX=0;entryY=0.5;entryDx=0;entryDy=0;fontFamily=Helvetica;fontSize=12;fontColor=#ffffff;fontStyle=0;" parent="1" source="25B0M3Xmif-6wFpoJRKW-112" target="25B0M3Xmif-6wFpoJRKW-108" edge="1">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="25B0M3Xmif-6wFpoJRKW-119" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;exitX=1;exitY=0.5;exitDx=0;exitDy=0;entryX=1;entryY=0.5;entryDx=0;entryDy=0;fontFamily=Helvetica;fontSize=12;fontColor=#ffffff;fontStyle=0;curved=1;" parent="1" source="25B0M3Xmif-6wFpoJRKW-3" target="25B0M3Xmif-6wFpoJRKW-109" edge="1">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="25B0M3Xmif-6wFpoJRKW-122" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;exitX=1;exitY=0.5;exitDx=0;exitDy=0;fontFamily=Helvetica;fontSize=12;fontColor=#ffffff;fontStyle=0;entryX=1;entryY=0.5;entryDx=0;entryDy=0;curved=1;" parent="1" source="25B0M3Xmif-6wFpoJRKW-101" target="25B0M3Xmif-6wFpoJRKW-51" edge="1">
          <mxGeometry relative="1" as="geometry">
            <mxPoint x="400" y="150" as="targetPoint" />
          </mxGeometry>
        </mxCell>
      </root>
    </mxGraphModel>
  </diagram>
</mxfile>
