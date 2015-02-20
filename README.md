# hello-world
just a simple respository
<html>
<body>
<h1>Intellisoft</h1>
 <table>  
   
    <tr>  
        <td>  
            <asp:Label ID="lblName" runat="server" Text="Name"></asp:Label>  
        </td>  
        <td>  
            <asp:TextBox ID="txtName" runat="server" MaxLength="20"></asp:TextBox>  
            <asp:RequiredFieldValidator ID="RequiredFieldValidator1" runat="server" ControlToValidate="txtName" ErrorMessage="Please Enter name"></asp:RequiredFieldValidator>
        </td>  
    </tr> 
         <tr>  
        <td>  
            <asp:Label ID="lblEmail" runat="server" Text="Email"></asp:Label>  
        </td>  
        <td>  
            <asp:TextBox ID="txtEmail" runat="server" TextMode="Email" MaxLength="50"></asp:TextBox>  
            <asp:RequiredFieldValidator ID="RequiredFieldValidator2" runat="server" ControlToValidate="txtEmail" ErrorMessage="Please Enter Email"></asp:RequiredFieldValidator>
            <asp:RegularExpressionValidator ID="RegularExpressionValidator1" runat="server" ControlToValidate="txtEmail" ErrorMessage="Email Should be in Well Format" ValidationExpression="\w+([-+.']\w+)*@\w+([-.]\w+)*\.\w+([-.]\w+)*"></asp:RegularExpressionValidator>
        </td>  
    </tr>
         <tr>  
        <td>  
          <asp:Label ID="lblDob" runat="server" Text="DOB"></asp:Label>   
        </td> 
             <td>  
                 <asp:TextBox  id="datepicker1" runat="server" TextMode="Date"></asp:TextBox>  
            <%--<asp:TextBox  id="datepicker" runat="server"></asp:TextBox>  --%>
                 <asp:RequiredFieldValidator ID="RequiredFieldValidator3" runat="server" ControlToValidate="datepicker1" ErrorMessage="Please Enter DOB"></asp:RequiredFieldValidator>
        </td>   
    </tr
        <tr>  
        <td>  
            <asp:Label ID="numbersonly11" runat="server" Text="Phone"></asp:Label>  
        </td>  
        <td>  
            <asp:TextBox ID="numbersonly" runat="server" class="input" value="" MaxLength="10" ></asp:TextBox>  
            <asp:RequiredFieldValidator ID="RequiredFieldValidator4" runat="server" ControlToValidate="numbersonly" ErrorMessage="Please Enter Mobile No."></asp:RequiredFieldValidator>
        </td>  
    </tr>     
    <tr>  
        <td class="auto-style1">  
            <asp:Label ID="lblAddress" runat="server" Text="Address"></asp:Label>  
        </td>  
        <td class="auto-style1">  
            <asp:TextBox ID="txtAddress" runat="server" TextMode="MultiLine" MaxLength="50"></asp:TextBox>  
            <asp:RequiredFieldValidator ID="RequiredFieldValidator5" runat="server" ControlToValidate="txtAddress" ErrorMessage="Please Enter Address"></asp:RequiredFieldValidator>
        </td>  
    </tr>  
    
 </table>  
</body>
</html>
