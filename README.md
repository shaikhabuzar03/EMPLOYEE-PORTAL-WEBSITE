# EMPLOYEE-PORTAL-WEBSITE
This is my first repository
<br>
Author - shaikh abuzar
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Company HR PORTAL</title>
    <link rel="icon" href="DALL·E 2024-11-11 01.04.47 - A horizontal cartoon-style image of a modern office with three people collaborating around a desk. One character is pointing at a laptop screen, anoth.webp">
    <style>
        body{
            margin:0;
            padding: 0;
            background-color: wheat;

            font-family:Arial, Helvetica, sans-serif ;
        }
        header{
            background-color:rgb(225, 181, 98) ;
            color: whitesmoke;
            text-align: center;
            padding: 2px;
        }
        .navitem{
            display: inline;
            padding: 15px;

        } 
        .navitem a{
            text-decoration: none;
            color: whitesmoke;
        }
        .registerform{
            
            width: max-content;
            margin-left: auto;
            margin-right: auto;
        }

        .employeetable{
            text-align: center;
        }
        table{
            margin-right: auto;
            margin-left: auto;
            width: 100%;
            border-collapse: collapse;
        }
        th,td{
            border: 1px solid black;
            padding: 8px;
        }
        .contactus{
            text-align: center;

        }
        .companyname{
            background-color: rgb(244, 190, 91);
            text-align: center;
            padding: 1px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome To Company HR Portal</h1>

        <nav>
        <ul>
            <li class="navitem"><a href="#employee-registration">Employee registration</a></li>
            <li class="navitem"><a href="#employee-directory">Employee Directory</a></li>
            <li class="navitem"><a href="#contact-us">Contact-Us</a></li>

        </ul>
        </nav>
    </header>
    
    <section id="employee-registration" class="registerform">
        <h2>Employee Registration</h2>
        <p>Fill The Below Form To Resgister as <em>Employee</em> </p>
        <form>
            <label for="name">Name: </label>
            <input type="text" id="name"><br><br>
            <label for="email">Email Id: </label>
            <input type="text" id="email"><br><br>
            <label for="password">Password: </label>
            <input type="password" id="password"><br><br>
            <label for="age">Age: </label>
            <select>
                <option>20</option>
                <option>19</option>
                <option>18</option>
                <option>17</option>
                <option>16</option>
                <option>15</option>
                <option>14</option>
                <option>13</option>
                <option>12</option>
                <option>11</option>
                <option>10</option>
                <option>09</option>
                <option>08</option>
                <option>07</option>
                <option>06</option>
                <option>05</option>
                <option>04</option>
                <option>03</option>
                <option>02</option>
                <option>01</option>
                
                <option>20</option>
                <option>20</option>
            </select><br><br>
            <label for="role">Select Role: </label>
            <select>
                <option>Software Engineer</option>
                <option>Product Manager</option>
                <option>Designer</option>
                <option>HR Represantative</option>
                <option>Speaker</option>
            </select><br><br>
            <label for="joining date">Select Joining Date: </label>
            <input type="date" id="joining date"><br><br>
            <label for="submit">Submit: </label>
            <input type="Submit" id="submit"><br>

        </form>
        

    </section>
    <section id="employee-directory" class="employeetable">
        <h2>Employee Directory</h2>
        <p>List of all registered employees.</p>
        <table>
            <tr>
            <th>Employee Id</th>
            <th>Employee Name</th>
            <th>Employee Role</th>
            </tr>
            <tr>
                <td>234</td>
                <td>Shaikh Talha</td>
                <td>Software Engineer</td>
            </tr>
            <tr>
                <td>235</td>
                <td>Pramodh Jadhav</td>
                <td>Software Engineer</td>
            </tr>
            <tr>
                <td>236</td>
                <td>Shaikh Ibrahim</td>
                <td>Designer</td>
            </tr>



        </table>

    </section>
    <section id="contact-us" class="contactus">
        <h2>Contact Us</h2>
        <p>You can contact at us shaikhabuzarhere03@gmail.com or visit us between
            9AM - 6PM.
        </p>
        <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3751.4009360484947!2d75.34001702376159!3d19.907502475346227!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x3bdba2aacb276267%3A0x53f4d18f03c0e85!2sNational%20Colony%2C%20Wankhede%20Nagar%2C%20Mahmoodpura%2C%20Chhatrapati%20Sambhaji%20Nagar%2C%20Maharashtra%20431003!5e0!3m2!1sen!2sin!4v1731265881932!5m2!1sen!2sin" width="400" height="300" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>

    </section>
    <footer class="companyname">
        <p>&copy; 2024 Zasma Tech Company</p>
    </footer>

</body>
</html>
