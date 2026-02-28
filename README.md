<!DOCTYPE html>
<html>
<head>
    <title>BMSIT Autonomous - III Semester Results</title>

    <style>
        body {
            font-family: Arial, Helvetica, sans-serif;
            background-color: #ffffff;
        }

        .container {
            width: 85%;
            margin: auto;
            margin-top: 30px;
        }

        h2, h3 {
            text-align: center;
            margin: 5px;
        }

        hr {
            border: 1px solid black;
        }

        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 15px;
        }

        table, th, td {
            border: 1px solid black;
        }

        th {
            background-color: #003366;
            color: white;
        }

        th, td {
            padding: 8px;
            text-align: center;
        }

        .input-section {
            text-align: center;
            margin-bottom: 20px;
        }

        input {
            padding: 8px;
            margin: 5px;
            width: 200px;
        }

        button {
            padding: 8px 20px;
            background-color: #003366;
            color: white;
            border: none;
            cursor: pointer;
        }

        button:hover {
            background-color: #0055aa;
        }

        .result-box {
            display: none;
        }

        .note {
            font-size: 13px;
            margin-top: 20px;
        }
    </style>
</head>

<body>

<div class="container">

    <h2>BMS INSTITUTE OF TECHNOLOGY AND MANAGEMENT</h2>
    <h3>(Autonomous)</h3>
    <hr>
    <h3>Result of III Semester B.E. Examination - January 2026</h3>

    <div class="input-section">
        <input type="text" id="usn" placeholder="Enter USN">
        <input type="password" id="password" placeholder="Enter Password">
        <br>
        <button onclick="checkResult()">Submit</button>
    </div>

    <div class="result-box" id="resultBox">

        <p><strong>USN:</strong> 1BY24EC060</p>
        <p><strong>Student Name:</strong> HASINI KV</p>
        <p><strong>Semester:</strong> 3</p>
        <p><strong>Branch:</strong> ELECTRONICS AND COMMUNICATION ENGINEERING</p>

        <table>
            <tr>
                <th>Subject Code</th>
                <th>Subject Name</th>
                <th>Internal</th>
                <th>External</th>
                <th>Total</th>
                <th>Result</th>
            </tr>

            <tr>
                <td>21EC31</td>
                <td>Mathematics-III</td>
                <td>42</td>
                <td>44</td>
                <td>86</td>
                <td>P</td>
            </tr>

            <tr>
                <td>21EC32</td>
                <td>Electronic Devices</td>
                <td>38</td>
                <td>40</td>
                <td>78</td>
                <td>P</td>
            </tr>

            <tr>
                <td>21EC33</td>
                <td>Digital System Design</td>
                <td>36</td>
                <td>43</td>
                <td>79</td>
                <td>P</td>
            </tr>

            <tr>
                <td>21EC34</td>
                <td>Network Analysis</td>
                <td>40</td>
                <td>42</td>
                <td>82</td>
                <td>P</td>
            </tr>

            <tr>
                <td>21EC35</td>
                <td>Signals & Systems</td>
                <td>37</td>
                <td>41</td>
                <td>78</td>
                <td>P</td>
            </tr>

            <tr>
                <td>21ECL36</td>
                <td>Electronic Devices Lab</td>
                <td>45</td>
                <td>46</td>
                <td>91</td>
                <td>P</td>
            </tr>

            <tr>
                <td>21ECL37</td>
                <td>Digital System Design Lab</td>
                <td>44</td>
                <td>45</td>
                <td>89</td>
                <td>P</td>
            </tr>
        </table>

        <h3>SGPA: 9.69</h3>
        <h3>Result: PASS</h3>

        <p class="note">
            Note: This is a computer-generated provisional result.
        </p>

    </div>

</div>

<script>
function checkResult() {
    var usn = document.getElementById("usn").value.trim().toUpperCase();
    var password = document.getElementById("password").value.trim();

    if(usn === "1BY24EC060" && password === "16554") {
        document.getElementById("resultBox").style.display = "block";
    } else {
        alert("Invalid USN or Password");
        document.getElementById("resultBox").style.display = "none";
    }
}
</script>

</body>
</html>
