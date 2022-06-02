# malijima.github.io

<!DOCTYPE html>
<html>
    <head>
        <title>Test Page</title>
        <style type="text/css">
            #mainHeader{
                text-align: right;
                background-color: brown;
                color:white;
                padding:10px;
            }
        </style>
    </head>

    <body> <!--comment balls-->
        <header id="mainHeader">
            <h1>My Website</h1>
        </header>
        <a href="blog.html"><h1>Heading One</h1></a> <!--headings and shit-->
        <h2>Heading Two</h2>
        <h3>Heading Three</h3>
        <h4>Heading Four</h4>
        <h5>Heading Five</h5>
        <h6>Heading Six</h6>

        <!--paragraph-->
        <p><strong>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Sunt saepe <em>sed unde pariatur, sapiente officiis molestiae repellat nemo</em> vel laboriosam eveniet aliquid nam nostrum illo reprehenderit aspernatur, dolorem natus voluptatum.
        </p></strong>
        <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Sunt saepe sed unde pariatur, <a href="http://google.com" target="_blank">sapiente</a> officiis molestiae repellat nemo vel laboriosam eveniet aliquid nam nostrum illo reprehenderit aspernatur, dolorem natus voluptatum.
        </p>
        <!--list shit-->
        <ul> <!--Unordered list-->
            <li>List Item 1</li>
            <li>List Item 2</li>
            <li>List Item 3</li>
        </ul>

        <ol> <!--ordered list-->
            <li>List Item 1</li>
            <li>List Item 2</li>
            <li>List Item 3</li>
        </ol>

        <table> <!--Table-->
            <thead>
                <tr>
                    <th>Name</th>
                    <th>Email</th>
                    <th>Age</th>
                </tr>
            </thead>
            <tbody>
                <tr>   
                    <td>Balls Lorem</td>
                    <td>ballslorem@lorem.com</td>
                    <td>76</td>
                </tr>
                <tr>   
                    <td>Balls Poop</td>
                    <td>ballspoop@lorem.com</td>
                    <td>5</td>
                </tr>
            </tbody>
        </table>

        <br>
        <hr>
        <br>
        <!--forms-->
        <form action="example.php" method="POST"> <!--action="example.php" method="POST" is server side shit-->
            <div>
                <label>First Name</label>
                <input type="text" name="firstName" placeholder="Enter first name">
            </div>
            <div>
                <label>Last Name</label>
                <input type="text" name="lastName">
            </div>
            <div>
                <label>Email</label>
                <input type="email" name="email">
            </div>
            <div>
                <label>Message</label>
                <textarea name="message"></textarea>
            </div>
            <br>
            <div>
                <label>Gender</label>
                <select name="gender">
                    <option value="male">Male</option>
                    <option value="female">Female</option>
                    <option value="other">Other</option>
                </select>
            </div>
            <div>
                <label>Age</label>
                <input type="number" name="age" value="30">
            </div>
            <br>
            <div>
                <label>Birthday</label>
                <input type="date" name="birthday">
            </div>
            <div> <!--Submit button (doesnt do anything)-->
                <input type="submit" name="submit" value="Submit">
            </div>
        </form>
        
        <br>
        <hr>
        <br>
        <div>
            <a href="image.jpg" target="_blank">
                <img src="image.jpg" alt="Pink bear love image">
            </a>
            
            <blockquote>
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Accusantium nulla suscipit eligendi vel reprehenderit tenetur culpa et non mollitia quidem sunt ut soluta dignissimos, provident officia assumenda earum laborum. Quibusdam.
            </blockquote>
        </div>
        

        <div style="margin-top: 500px"></div>
    </body>
</html>
