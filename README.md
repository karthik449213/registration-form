<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <FORM ACTION="/REGISTER" METHOD="POST">
        <TABLE BORDER="1">
            <TR>
                <TH>ENTER YOUR DTEAILS</TH>
            </TR>
            <TR>
                <TD><LABEL FOR="USERNAME">NAME:</LABEL>
                <INPUT TYPE="TEXT" ID="USERNAME" NAME="USERNAME"></TD>
            </TR>
            <TR>
                <TD><LABEL FOR="PASSWORD">PASSWORD</LABEL>
                <INPUT TYPE="PASSWORD" ID="PASSWORD" NAME="PASSWORD" PLACEHOLDER="ENTER PASSWORD"></TD>

            </TR>
            <TR>
                <TD><LABEL FOR="EMAIL" >EMAIL:</LABEL>
                <INPUT TYPE="EMAIL" ID="EMAIL" NAME="EMAIL" PLACEHOLDER="ENTER EMAIL"></TD>
            </TR>
            <TR>
                <TD><LABEL FOR="GENDER">GENDER:</LABEL>
                <INPUT TYPE="RADIO" ID="MALE" NAME="GENDER" VALUE="MALE">MALE
                <INPUT TYPE="RADIO" ID="FEMALE" NAME="GENDER" VALUE="FEMALE">FEMALE</TD>
            </TR>
            <TR>
                <TD><LABEL FOR="COUNTRY">COUNTRY</LABEL>
                <SELECT>
                    <OPTION COUNTRY="US">US</OPTION>
                    <OPTION COUNTRY="UK">UK</OPTION>
                    <OPTION COUNTRY="LONDON">LONDON</OPTION>
                </SELECT></TD>
            </TR>
            <TR>
                <TD><BUTTON TYPE="SUBMIT">REGISTER</BUTTON>
                <BUTTON TYPE=RESET>REFRESH</BUTTON></TD>
            </TR>
        </TABLE>
    </FORM>
      
</body>
</html>
