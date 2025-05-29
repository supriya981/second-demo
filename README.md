# second-demo
this is my second repository
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Forms</title>
</head>

<body>
    <h2> This is form </h2>
    <form action="backend.php">

        <label for="name">Name</label>
        <div>
            <input type="text" name="myname" id="name">
        </div>
        <br>
        <div>
            role:<input type="text" name="myrole">
        </div><br>
        <div>
            Email:<input type="email" name="myemail">
        </div><br>
        <br>
        <div>
            Date:<input type="Date" name="mydate">
        </div>
        <br>
        <div>
            Bonus:<input type="number" name="mybonus">
        </div>
        <br>
        <div>
            Are you Eligible:<input type="checkbox" name="myeligiblity" checked>
        </div>
        <br>
        <div>
            Gender:Male<input type="radio" name="mygender">Female<input type="radio" name="mygender">
            other<input type="radio" name="mygender">


        </div><br>
        <div>
            write about yourself:<br><textarea name="mytext" cols="40" rows="10"></textarea>
        </div>
        <br>
        <div>
            <label for="car">Car</label>
            <select name="mycar" id="car">
                <option value="indica">indica</option>
                <option value="creta">creta</option>
            </select>
        </div>
        <br>
        <div>
            <!-- for submit button -->
            <input type="submit" value="Submit Now">

            <input type="reset" value="reset Now">
        </div>

    </form>
    <a href="https://google.com" target="_blank">Go to Goggle</a><br>

</body>

</html>
