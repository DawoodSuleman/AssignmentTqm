# AssignmentTqm
Save:

 HttpCookie abc = new HttpCookie("username");
        Response.Cookies["uername"].Value = TextBox1.Text;
        Response.Cookies["Username"].Expires = DateTime.Now.AddDays(1);
        Response.Cookies.Add(abc);





Retrieve:



if (Request.Cookies["username"] != null)
        {
            HttpCookie xyz = Request.Cookies["username"];
            Label1.Text = Server.HtmlEncode(xyz.Value);
        }
