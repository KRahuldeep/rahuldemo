<!DOCTYPE html>
<html lang="en">
<body bgcolor="skyblue">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Vertical Group</title>
<style>
   
    .group 
{
        display: flex;
        flex-direction: column;
        gap: 20px;
    }

    .group button 
{
        padding: 20px;
        border: 1px solid #ccc;
        border-radius: 5px;
        background-color: #E86C6C;
        cursor: pointer;
        transition: background-color 0.4s;
    }

    .group button:hover 
{
        background-color: #e0e0e0;
    }
</style>
</head>


<div class="group" >
    <button onclick="navigate('profile')">Profile</button>
    <button onclick="navigate('history')">History</button>
    <button onclick="navigate('payments')">Payments</button>
    <button onclick="navigate('refer')">Refer and Earn</button>
    <button onclick="navigate('insurance')">Insurance</button>
    <button onclick="navigate('support')">Support</button>
    <button onclick="navigate('about')">About</button>

</div>


</body>
</html>
