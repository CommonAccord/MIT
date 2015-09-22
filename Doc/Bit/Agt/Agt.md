Intro.=[Z/Agt/Agt_Intro.md]

End.=[Z/Agt/Agt_End.md]

Attach.=[Bit/Attach]
  
Model.Root={DocBody}

DocBody={Doc}

Doc=<font color="grey">{MessageToUser}</font><center><h4>{Heading.Sec}</h4></center><br>{sec} 

Heading.Sec={Ti}

sec={Intro.Sec} {xlist} {End.Sec}

xlist={Olist}

Olist=<ol><li>{Secs}</li></ol>

Note=To make blank - could be improved:

null=<b></b>

=[Z/Agt/DT_Base.md]
