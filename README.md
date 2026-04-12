# Student-Management-System<br>
com.student.management<br>
 │<br>
├── controller<br>
├── service<br>
├── repository<br>
├── model<br>
├── dto<br>
└── config<br>

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Architecture Diagram</title>
<style>
    body {
        font-family: Arial, sans-serif;
        text-align: center;
        margin-top: 40px;
    }

    .row {
        display: flex;
        justify-content: center;
        align-items: center;
        margin: 20px 0;
        gap: 20px;
    }

    .box {
        padding: 15px 25px;
        border-radius: 10px;
        color: white;
        font-weight: bold;
        min-width: 140px;
    }

    .orange { background-color: #ff7a3d; }
    .blue { background-color: #3b82f6; }

    .arrow {
        font-size: 20px;
        font-weight: bold;
    }

    .vertical {
        margin: 10px 0;
        font-size: 20px;
    }
</style>
</head>
<body>

<h2>Project Architecture</h2>

<div class="row">
    <div class="box orange">Browser</div>
    <div class="arrow">→</div>
    <div class="box orange">Controller</div>
    <div class="arrow">↔</div>
    <div class="box orange">Service</div>
    <div class="arrow">↔</div>
    <div class="box orange">Repository</div>
    <div class="arrow">↔</div>
    <div class="box blue">Database</div>
</div>

<div class="vertical">↓</div>

<div class="row">
    <div class="box blue">View (Thymeleaf Template)</div>
</div>

</body>
</html>
