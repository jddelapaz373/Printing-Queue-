
<!DOCTYPE html>
<html>
<head>
    <title>Student Printing Queue</title>

    <style>
        * {
            box-sizing: border-box;
        }

        body {
            font-family: Arial;
            margin: 0;
            background: #f2f2f2;
        }

        .page {
            display: none;
            padding: 30px 15px;
            min-height: 90vh;
        }

        .active {
            display: block;
        }

        .box {
            background: white;
            padding: 25px;
            max-width: 900px;
            width: 100%;
            margin: 30px auto;
            border-radius: 8px;
        }

        h1, h2 {
            text-align: center;
        }

        input, select {
            width: 100%;
            padding: 10px;
            margin: 6px 0 12px;
        }

        button {
            padding: 10px 15px;
            margin: 5px;
            cursor: pointer;
        }

        .main-button {
            width: 100%;
            margin: 5px 0;
        }

        nav {
            background: #333;
            padding: 12px;
            text-align: center;
        }

        nav button {
            color: white;
            background: #555;
            border: none;
        }

        nav button:hover {
            background: #777;
        }

        .message {
            text-align: center;
            margin-top: 10px;
        }

        .link {
            text-align: center;
            margin-top: 15px;
        }

        .link button {
            background: none;
            border: none;
            color: blue;
            padding: 0;
        }

        .stats {
            text-align: center;
            margin: 20px 0;
        }

        .stat-box {
            display: inline-block;
            padding: 15px 25px;
            margin: 5px;
            border: 1px solid #ccc;
        }

        /* Makes tables fit inside the box */
        .table-container {
            width: 100%;
            overflow-x: auto;
        }

        table {
            width: 100%;
            min-width: 650px;
            border-collapse: collapse;
            margin-top: 20px;
        }

        th, td {
            border: 1px solid #aaa;
            padding: 8px;
            text-align: center;
            word-wrap: break-word;
        }

        th {
            background: #eee;
        }

        td button {
            padding: 6px 8px;
            margin: 2px;
        }

        @media (max-width: 600px) {

            .box {
                padding: 15px;
            }

            table {
                font-size: 13px;
            }

            th, td {
                padding: 6px;
            }

            nav button {
                padding: 8px;
                margin: 2px;
            }
        }
    </style>
</head>

<body>


<!-- ================= LOGIN ================= -->

<div id="login" class="page active">

    <div class="box">

        <h1>STUDENT PRINTING QUEUE</h1>

        <h2>Login</h2>

        <input
            type="text"
            id="loginUsername"
            placeholder="Username">

        <input
            type="password"
            id="loginPassword"
            placeholder="Password">

        <button
            class="main-button"
            onclick="login()">
            Login
        </button>

        <p
            id="loginMessage"
            class="message">
        </p>

        <div class="link">

            <p>
                Don't have an account?
                <button onclick="showPage('signup')">
                    Sign Up
                </button>
            </p>

        </div>

    </div>

</div>


<!-- ================= SIGN UP ================= -->

<div id="signup" class="page">

    <div class="box">

        <h1>STUDENT PRINTING QUEUE</h1>

        <h2>Sign Up</h2>

        <input
            type="text"
            id="signupUsername"
            placeholder="Create Username">

        <input
            type="password"
            id="signupPassword"
            placeholder="Create Password">

        <input
            type="password"
            id="signupConfirm"
            placeholder="Confirm Password">

        <button
            class="main-button"
            onclick="signup()">
            Sign Up
        </button>

        <p
            id="signupMessage"
            class="message">
        </p>

        <div class="link">

            <p>
                Already have an account?
                <button onclick="showPage('login')">
                    Login
                </button>
            </p>

        </div>

    </div>

</div>


<!-- ================= NAVIGATION ================= -->

<nav id="navigation" style="display:none;">

    <button onclick="showPage('home')">
        Home
    </button>

    <button onclick="showPage('request')">
        Print Request
    </button>

    <button onclick="showPage('queue')">
        Queue
    </button>

    <button onclick="showPage('history')">
        History
    </button>

    <button onclick="logout()">
        Logout
    </button>

</nav>


<!-- ================= HOME ================= -->

<div id="home" class="page">

    <div class="box">

        <h1>HOME</h1>

        <h2>
            Welcome, <span id="welcomeUser"></span>
        </h2>

        <div class="stats">

            <div class="stat-box">
                <b>Waiting</b>
                <p id="waiting">0</p>
            </div>

            <div class="stat-box">
                <b>Completed</b>
                <p id="completed">0</p>
            </div>

        </div>

        <p style="text-align:center;">
            Use the navigation buttons above to manage printing requests.
        </p>

    </div>

</div>


<!-- ================= PRINT REQUEST ================= -->

<div id="request" class="page">

    <div class="box">

        <h1>PRINT REQUEST</h1>

        <label>Student Name</label>

        <input
            type="text"
            id="studentName"
            placeholder="Enter student name">


        <label>Student ID</label>

        <input
            type="text"
            id="studentID"
            placeholder="Enter student ID">


        <label>Number of Pages</label>

        <input
            type="number"
            id="pages"
            min="1"
            placeholder="Enter number of pages">


        <label>Print Type</label>

        <select id="type">

            <option value="Black & White">
                Black & White
            </option>

            <option value="Colored">
                Colored
            </option>

        </select>


        <button
            class="main-button"
            onclick="addRequest()">
            Add to Queue
        </button>


        <p
            id="requestMessage"
            class="message">
        </p>

    </div>

</div>


<!-- ================= QUEUE ================= -->

<div id="queue" class="page">

    <div class="box">

        <h1>PRINTING QUEUE</h1>

        <div class="table-container">

            <table>

                <thead>

                    <tr>
                        <th>Queue</th>
                        <th>Student</th>
                        <th>ID</th>
                        <th>Pages</th>
                        <th>Type</th>
                        <th>Status</th>
                        <th>Action</th>
                    </tr>

                </thead>

                <tbody id="queueTable"></tbody>

            </table>

        </div>

    </div>

</div>


<!-- ================= HISTORY ================= -->

<div id="history" class="page">

    <div class="box">

        <h1>PRINTING HISTORY</h1>

        <div class="table-container">

            <table>

                <thead>

                    <tr>
                        <th>Student</th>
                        <th>ID</th>
                        <th>Pages</th>
                        <th>Type</th>
                        <th>Status</th>
                    </tr>

                </thead>

                <tbody id="historyTable"></tbody>

            </table>

        </div>

    </div>

</div>


<script>

/* ================= DATA ================= */

let users =
    JSON.parse(localStorage.getItem("printingUsers")) || {};

let requests =
    JSON.parse(localStorage.getItem("printingRequests")) || [];

let currentUser = null;


/* ================= PAGE NAVIGATION ================= */

function showPage(page) {

    if (
        currentUser == null &&
        page != "login" &&
        page != "signup"
    ) {
        page = "login";
    }

    let pages = document.querySelectorAll(".page");

    pages.forEach(function(p) {
        p.classList.remove("active");
    });

    document.getElementById(page).classList.add("active");


    if (currentUser != null) {

        document.getElementById("navigation")
            .style.display = "block";

        updateHome();
        displayQueue();
        displayHistory();

        document.getElementById("welcomeUser")
            .innerHTML = currentUser;

    }
}


/* ================= SIGN UP ================= */

function signup() {

    let username =
        document.getElementById("signupUsername").value.trim();

    let password =
        document.getElementById("signupPassword").value;

    let confirm =
        document.getElementById("signupConfirm").value;


    if (username == "" || password == "" || confirm == "") {

        document.getElementById("signupMessage")
            .innerHTML = "Please complete all fields.";

        return;
    }


    if (password != confirm) {

        document.getElementById("signupMessage")
            .innerHTML = "Passwords do not match.";

        return;
    }


    if (users[username]) {

        document.getElementById("signupMessage")
            .innerHTML = "Username already exists.";

        return;
    }


    users[username] = {
        password: password
    };


    localStorage.setItem(
        "printingUsers",
        JSON.stringify(users)
    );


    document.getElementById("signupMessage")
        .innerHTML = "Account created successfully.";


    document.getElementById("signupUsername").value = "";
    document.getElementById("signupPassword").value = "";
    document.getElementById("signupConfirm").value = "";


    setTimeout(function() {
        showPage("login");
    }, 1000);
}


/* ================= LOGIN ================= */

function login() {

    let username =
        document.getElementById("loginUsername").value.trim();

    let password =
        document.getElementById("loginPassword").value;


    if (
        users[username] &&
        users[username].password == password
    ) {

        currentUser = username;


        document.getElementById("loginUsername").value = "";
        document.getElementById("loginPassword").value = "";


        document.getElementById("loginMessage")
            .innerHTML = "";


        document.getElementById("navigation")
            .style.display = "block";


        showPage("home");

    }
    else {

        document.getElementById("loginMessage")
            .innerHTML = "Invalid username or password.";

    }
}


/* ================= LOGOUT ================= */

function logout() {

    currentUser = null;

    document.getElementById("navigation")
        .style.display = "none";

    showPage("login");
}


/* ================= ADD PRINT REQUEST ================= */

function addRequest() {

    let name =
        document.getElementById("studentName").value.trim();

    let id =
        document.getElementById("studentID").value.trim();

    let pages =
        document.getElementById("pages").value;

    let type =
        document.getElementById("type").value;


    if (name == "" || id == "" || pages == "") {

        document.getElementById("requestMessage")
            .innerHTML =
            "Please complete all fields.";

        return;
    }


    if (pages <= 0) {

        document.getElementById("requestMessage")
            .innerHTML =
            "Number of pages must be at least 1.";

        return;
    }


    let request = {

        name: name,

        id: id,

        pages: pages,

        type: type,

        status: "Waiting",

        user: currentUser

    };


    requests.push(request);


    localStorage.setItem(
        "printingRequests",
        JSON.stringify(requests)
    );


    document.getElementById("studentName").value = "";
    document.getElementById("studentID").value = "";
    document.getElementById("pages").value = "";


    document.getElementById("requestMessage")
        .innerHTML =
        "Print request added successfully.";


    updateHome();
    displayQueue();
}


/* ================= DISPLAY QUEUE ================= */

function displayQueue() {

    let table =
        document.getElementById("queueTable");

    table.innerHTML = "";

    let number = 1;


    requests.forEach(function(request, index) {

        if (request.status == "Waiting") {

            table.innerHTML += `

                <tr>

                    <td>${number}</td>

                    <td>${request.name}</td>

                    <td>${request.id}</td>

                    <td>${request.pages}</td>

                    <td>${request.type}</td>

                    <td>${request.status}</td>

                    <td>

                        <button
                            onclick="completeRequest(${index})">
                            Complete
                        </button>

                        <button
                            onclick="deleteRequest(${index})">
                            Delete
                        </button>

                    </td>

                </tr>

            `;

            number++;
        }

    });


    if (number == 1) {

        table.innerHTML = `
            <tr>
                <td colspan="7">
                    No printing requests.
                </td>
            </tr>
        `;
    }
}


/* ================= COMPLETE REQUEST ================= */

function completeRequest(index) {

    requests[index].status = "Completed";


    localStorage.setItem(
        "printingRequests",
        JSON.stringify(requests)
    );


    displayQueue();
    displayHistory();
    updateHome();
}


/* ================= DELETE REQUEST ================= */

function deleteRequest(index) {

    if (!confirm("Delete this printing request?")) {
        return;
    }


    requests.splice(index, 1);


    localStorage.setItem(
        "printingRequests",
        JSON.stringify(requests)
    );


    displayQueue();
    displayHistory();
    updateHome();
}


/* ================= HISTORY ================= */

function displayHistory() {

    let table =
        document.getElementById("historyTable");

    table.innerHTML = "";


    let found = false;


    requests.forEach(function(request) {

        if (request.status == "Completed") {

            found = true;

            table.innerHTML += `

                <tr>

                    <td>${request.name}</td>

                    <td>${request.id}</td>

                    <td>${request.pages}</td>

                    <td>${request.type}</td>

                    <td>${request.status}</td>

                </tr>

            `;
        }

    });


    if (!found) {

        table.innerHTML = `
            <tr>
                <td colspan="5">
                    No printing history.
                </td>
            </tr>
        `;
    }
}


/* ================= HOME COUNTERS ================= */

function updateHome() {

    let waiting = 0;
    let completed = 0;


    requests.forEach(function(request) {

        if (request.status == "Waiting") {
            waiting++;
        }

        if (request.status == "Completed") {
            completed++;
        }

    });


    document.getElementById("waiting")
        .innerHTML = waiting;

    document.getElementById("completed")
        .innerHTML = completed;
}


/* ================= START ================= */

showPage("login");

</script>

</body>
</html>

