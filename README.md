<!DOCTYPE html>
<html lang="en" data-theme="bumblebee">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!-- css -->
    <link rel="stylesheet" href=""C:\Users\harih\Downloads\style.css"">
    <!--Icons-->
    <link href="C:\Users\harih\Downloads\style.css" rel='stylesheet'>
    <link rel="icon" type="image/x-icon" href="C:\Users\harih\Downloads\to do.png">

    <title>Todolist</title>
</head>

<body>

    <!-- main todo container -->
    <div class="container">
        <!-- header that has input and add button -->
        <header>
            <h1>Todo List</h1>

            <div class="input-section">
                <input id="todo-input" type="text" placeholder="📑 Add your todo here.."
                    class="input w-full max-w-xs" />
                <button id="add-button" class="btn btn-add ">
                    <i class="bx bx-plus bx-sm"></i>
                </button>
            </div>
        </header>

        <!-- delete buttons -->

        <div class="todos-filter">

            <button id="delete-selected" class="btn btn-ghost delete-selected-btn">
                Delete Selected
            </button>
            <button id="delete-all" class="btn btn-ghost delete-all-btn">
                Delete All
            </button>
        </div>


        <!-- this is the dynamic content which dds ups all the todos -->
        <ul id="all-todos" class="todos-list">

        </ul>


        <!-- dropdown throgh which we can apply filters -->
        <div class="filters">
            <div class="dropdown">
                <button class="dropbtn">Filter</button>
                <div class="dropdown-content">
                    <a href="#" id="all">All</a>
                    <a href="#" id="rem">Pending</a>
                    <a href="#" id="com">Completed</a>
                </div>
            </div>

            <!-- value showing completed task and all -->
            <div class="completed-task">
                <p>Completed: <span id="c-count">0</span></p>
            </div>
            <div class="remaining-task">
                <p>Total Tasks: <span id="r-count">0</span></p>
            </div>
        </div>
    </div>

    <!-- JS -->
    <script src=""C:\Users\harih\Downloads\index2.js""></script>

</body>

</html>
