<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Abyssinica+SIL&family=Alkalami&family=Poppins:wght@200&display=swap');
        @import url('https://fonts.googleapis.com/css2?family=Abyssinica+SIL&family=Alkalami&family=Poppins:wght@200&display=swap');
        @import url('https://fonts.googleapis.com/css2?family=Abyssinica+SIL&family=Alkalami&family=Merriweather:wght@700&family=Poppins:wght@200&display=swap');

        * {
            margin: 0;
            padding: 0;
            text-decoration: none;
            list-style: none;
        }

        body {
            background-color: rgb(4, 27, 43);
        }

        .banner {

            font-family: 'Abyssinica SIL', serif;

        }

        .navbar {
            display: flex;
            font-size: 17px;
            color: white;

        }

        .logo {

            margin: 0 25px;
        }

        h1 {
            margin: 19px;
            color: white;

        }

        .navbar ul {

            margin: 30px 0 0 446px;

        }

        .navbar ul li {
            display: inline-block;
            padding: 0 9px;
            position: relative;

        }

        .navbar ul li a {
            text-decoration: none;
            color: rgb(255, 90, 0);
        }

        .navbar ul li::after {
            content: '';
            height: 1px;
            width: 0;
            background: rgb(255, 90, 0);

            position: absolute;
            left: 0;
            bottom: -10px;
            transition: 0.3s;

        }

        .navbar ul li:hover::after {
            width: 100%;
        }

        p {
            color: rgb(255, 90, 0);
            margin: 0 10px;

        }

        .box {
            width: 50%;
        }

        .box3 {
            color: rgb(255, 90, 0);


        }


        .img2 {
            width: 521px;
            height: 295px;

            padding: 76px 75px;
            border-radius: 80px;
        }

        .tab {
            display: flex;
            justify-content: center;
            align-items: center;
        }

        .tabel {
            margin: 0;
            padding: 0;
            font-family: 'Abyssinica SIL', serif;
            color: rgb(255, 90, 0);

            display: flex;
            justify-content: center;
            align-items: center;
        }

        .size {
            padding: 0 220px;
        }

        .img {
            text-align: end;
            padding: 78px 0;

        }

        .tabel2 {
            color: rgb(255, 90, 0);
            font-family: 'Abyssinica SIL', serif;

        }

        .vid {

            display: flex;
            justify-content: center;
            align-items: center;

        }

        .container {
            font-family: 'Abyssinica SIL', serif;
            display: flex;
        }

        .audio {
            display: flex;
            justify-content: center;
            align-items: center;
        }

        .click {
            display: flex;
            justify-content: center;
            align-content: center;
        }

        .click a {
            text-decoration: none;
        }


        .col {
            display: flex;
            align-content: center;
            justify-content: center;
            flex-wrap: wrap;
        }

        .last {
            padding: 141px 79px;
            width: 100%;

        }

        .last1 {
            width: 25%;
        }

        .l1 {}

        .last1 h3 {
            color: white;
            margin-bottom: 25px;
            position: relative;
            font-family: 'Merriweather', serif;
        }

        .last1 h3::before {
            content: "";
            position: absolute;

            height: 2px;
            width: 50px;
            left: 0;
            bottom: -8px;
            background: rgb(255, 90, 0);
        }

        .last1 ul li a {
            color: white;
            display: block;
            font-size: 1.1rem;
            transition: .4s;
        }

        .last1 ul li a:hover {
            color: rgb(187, 69, 69);
            transform: translateX(-12px);
            font-family: 'Merriweather', serif;

        }

        .tabel22 {
            display: flex;
            justify-content: space-between;
            color: rgb(255, 90, 0);
            padding: 0 20px;

        }

        .tab1 {
            display: flex;
            justify-content: end;
            padding: 0 180px;
            font-family: 'Merriweather', serif;
            text-transform: uppercase;

        }

        .space {
            width: 38vw;
            height: 100vh;
            padding: 242px 8px;
            border-radius: 243px;
        }

        .lm a {
            color: white;
        }
    </style>
</head>

<body>

    <div class="banner">

        <div class="navbar">

            <a href="https://www.iul.ac.in/" target="_blank"> <img
                    src="https://upload.wikimedia.org/wikipedia/en/8/86/Integral_University%2C_Lucknow_logo.png"
                    class="logo" height="90px"> </a>
            <h1 class="box3">Integral University </h1>
            <ul>

                <li><a href="https://www.iul.ac.in/About/Overview/Overview.aspx" target="_blank">About</a></li>
                <li><a href="https://iul.ac.in/Department/Engineering.aspx" target="_blank">Faculties</a></li>

                <li><a href="https://iul.ac.in/admissioninfo/FeeInd.aspx" target="_blank">Program</a></li>
                <li><a href="https://www.iul.ac.in/Contactus.aspx" target="_blank">Contact Us</a></li>

            </ul>


        </div>
    </div>
    <hr>


    <div class="container">




        <div class="box">
            <h1>Department of Computer Application</h1>
            <p>The Computer Applications program is designed to provide the skills needed in the use of application
                software
                on a computer. Applications covered include word processing, spreadsheets, databases, desktop
                publishing,
                the Internet, and the Windows operating systems. Courses will provide the student skills to work in
                various
                office settings.</p>





            <h1>Knowledge and Skills</h1>

            <p>Skills and knowledge gained in the program include the ability to:</p>



            <p> Produce business documents such as letters memos, tables, and reports utilizing keyboarding,
                proofreading and editing techniques.</p>

            <p>Use word processing software to produce documents applying business formatting including
                features and functions.</p>
            <p>Create, edit and print spreadsheet documents</p>
            <p>Create, edit, and print database files.</p>
            <p>Use and apply software to produce professional business presentations.</p>

        </div>

        <div class="list">

            <a href="https://www.iul.ac.in/" target="_blank"> <img class="img2"
                    src="http://drive.google.com/uc?export=view&id=1Pev_0jbLmzwmO9thfPrjQv8ilZdKPKJe ">
            </a>
        </div>
    </div>


    <div class="click">

        <a href="https://www.wikipedia.org/" target="_blank">
            <h1> Click here...!</h1>
        </a>
    </div>







    <div class="tabel3">
        <div class="tab">
            <h1> TIME Table(BCA-3, Group-A)</h1>
        </div>

        <div class="tabel">
            <table border="1" cellspacing="0" align="center">
                <tr>
                    <td align="center" height="50" width="100"><br>
                        <b></b></br>
                    </td>
                    <td align="center" height="50" width="100">
                        <b>I<br>9:00-9:50</b>
                    </td>
                    <td align="center" height="50" width="100">
                        <b>II<br>9:50-10:40</b>
                    </td>
                    <td align="center" height="50" width="100">
                        <b>III<br>10:40-11:30</b>
                    </td>
                    <td align="center" height="50" width="100">
                        <b>11:30-12:20</b>
                    </td>
                    <td align="center" height="50" width="100">
                        <b>IV<br>12:20-1:30</b>
                    </td>
                    <td align="center" height="50" width="100">
                        <b>V<br>1:30-2:20</b>
                    </td>
                    <td align="center" height="50" width="100">
                        <b>VI<br>2:20-3:10</b>
                    </td>
                    <td align="center" height="50" width="100">
                        <b>VII<br>3:10-4:00</b>
                    </td>
                </tr>
                <tr>
                    <td align="center" height="50">
                        <b>Monday</b>
                    </td>
                    <td align="center" height="50">CA-301</td>
                    <td align="center" height="50">CA-302</td>
                    <td align="center" height="50">CA-304</td>
                    <td align="center" height="50">CA-307</td>
                    <td rowspan="6" align="center" height="50">
                        <h2>L<br>U<br>N<br>C<br>H</h2>
                    </td>
                    <td colspan="" align="center" height="50"></td>
                    <td colspan="2" align="center" height="50">CA-312
                    </td>
                </tr>
                <tr>
                    <td align="center" height="50">
                        <b>Tuesday</b>
                    </td>
                    <td align="center" height="50">CA-307
                    </td>
                    <td colspan="3" align="center" height="50">CA-310</td>
                    <td align="center" height="50"></td>
                    <td align="center" height="50">CA-304</td>
                    <td align="center" height="50">CA-301</td>
                </tr>
                <tr>
                    <td align="center" height="50">
                        <b>Wednesday</b>
                    </td>
                    <td align="center" height="50">CA-303</td>
                    <td align="center" height="50">CA-303</td>
                    <td align="center" height="50">PPP(APTI)</td>
                    <td align="center" height="50"></td>
                    <td align="center" height="50"> </td>
                    <td align="center" height="50">CA-302</td>
                    <td align="center" height="50">CA-304</td>
                </tr>
                <tr>
                    <td align="center" height="50">
                        <b>Thursday</b>
                    </td>
                    <td align="center" height="50">CA-307</td>
                    <td align="center" height="50">CA-304</td>
                    <td align="center" height="50">CA-302</td>
                    <td align="center" height="50"></td>
                    <td align="center" height="50">301</td>
                    <td align="center" height="50">PPP(SOFT SKILL)</td>
                    <td align="center" height="50"></td>


                </tr>
                <tr>
                    <td align="center" height="50">
                        <b>Friday</b>
                    </td>
                    <td colspan="3" align="center" height="50">CA-311/CA-310
                    </td>
                    <td align="center" height="50">CA-303</td>
                    <td align="center" height="50"></td>
                    <td colspan="2" align="center" height="50">CA-312</td>

                </tr>
                <tr>
                    <td align="center" height="50">
                        <b>Saturday</b>
                    </td>
                    <td align="center" height="50">CA-303</td>
                    <td align="center" height="50">CA-302</td>
                    <td align="center" height="50">CA-301</td>
                    <td align="center" height="50">CA-307</td>
                    <td align="center" height="50"></td>
                    <td align="center" height="50"></td>
                    <td align="center" height="50"></td>

                    </td>

                </tr>

            </table>
        </div>

    </div>
    <br>
    <hr>

    <h1 class="tab1">Infrastructure</h1>
    <div class="tabel22">

       <a href="https://www.iul.ac.in/" target="_blank"> <img src="http://drive.google.com/uc?export=view&id=1X7tQXUsKMOGu-mWipeK2urGp64LfulLg" <div class="space"></a>
        <table border="1" cellspacing="0" align="center" cellpadding="20px 10px 20px 10px">

            <tr>

                <td align="center" height="50" width="100">
                    <b><br>ROOM</b>
                </td>
                <td align="center" height="50" width="100">
                    <b><br>NAME</b>
                </td>
                <td align="center" height="50" width="100">
                    <b><br>AREA</b>
                </td>
                <td align="center" height="50" width="100">
                    <b><br>CAPACITY</b>
                </td>
                <td align="center" height="50" width="100">
                    <b><br>CONFIGURATION</b>
                </td>

            </tr>

            <tr>
                </td>
                <td align="center" height="50" width="100">
                    <b><br>CA-1</b>
                </td>
                <td align="center" height="50" width="100">
                    <b><br> Web Development Lab</b>
                </td>
                <td align="center" height="50" width="100">
                    <b><br>860 Sq.Ft.</b>
                </td>
                <td align="center" height="50" width="100">
                    <b><br>30 Students</b>
                </td>
                <td align="center" height="50" width="100">
                    <b><br>C2D/320 GB/18.5 TFT/ HP 3090 PC/Operating System-UBUNTU</b>
                </td>

            </tr>



            <tr>
                </td>
                <td align="center" height="50" width="100">
                    <b><br>CA-2</b>
                </td>
                <td align="center" height="50" width="100">
                    <b><br>Project Lab</b>
                </td>
                <td align="center" height="50" width="100">
                    <b><br>860 Sq.Ft.</b>
                </td>
                <td align="center" height="50" width="100">
                    <b><br>30 Students</b>
                </td>
                <td align="center" height="50" width="100">
                    <b><br>C2D/320 GB/18.5 TFT/ HP 3090 PC/Operating System-UBUNTU</b>
                </td>

            </tr>


            <tr>
                </td>
                <td align="center" height="50" width="100">
                    <b><br>CA-3</b>
                </td>
                <td align="center" height="50" width="100">
                    <b><br>Graphics & Multimedia Lab</b>
                </td>
                <td align="center" height="50" width="100">
                    <b><br>1020 Sq.Ft.</b>
                </td>
                <td align="center" height="50" width="100">
                    <b><br>30 Students</b>
                </td>
                <td align="center" height="50" width="100">
                    <b><br>I5/500GB/DVDRW/18.5 TFT/HP3330PC/ Operating System-Windows 8</b>
                </td>

            </tr>




            <tr>
                </td>
                <td align="center" height="50" width="100">
                    <b><br>CA-4</b>
                </td>
                <td align="center" height="50" width="100">
                    <b><br>Database Lab</b>
                </td>
                <td align="center" height="50" width="100">
                    <b><br>910 Sq.Ft.</b>
                </td>
                <td align="center" height="50" width="100">
                    <b><br>30 Students</b>
                </td>
                <td align="center" height="50" width="100">
                    <b><br>I5/500GB/DVDRW/18.5 TFT/HP3330PC/ Operating System-Windows 8</b>
                </td>

            </tr>


            <tr>
                </td>
                <td align="center" height="50" width="100">
                    <b><br>CA-5</b>
                </td>
                <td align="center" height="50" width="100">
                    <b><br> Open Source Lab</b>
                </td>
                <td align="center" height="50" width="100">
                    <b><br>890 Sq.Ft.</b>
                </td>
                <td align="center" height="50" width="100">
                    <b><br>30 Students</b>
                </td>
                <td align="center" height="50" width="100">
                    <b><br>I5/500GB/DVDRW/18.5 TFT/HP3330PC/ Operating System-Windows 8</b>
                </td>

            </tr>


            <tr>
                </td>
                <td align="center" height="50" width="100">
                    <b><br>CA-6</b>
                </td>
                <td align="center" height="50" width="100">
                    <b><br> Programming Lab</b>
                </td>
                <td align="center" height="50" width="100">
                    <b><br>1280 Sq.Ft.b>
                </td>
                <td align="center" height="50" width="100">
                    <b><br>30 Students</b>
                </td>
                <td align="center" height="50" width="100">
                    <b><br>C2D/32GB/2GB/18.5 TFT/DVDRW/ Operating System-UBUNTU</b>
                </td>

            </tr>



            <tr>
                </td>
                <td align="center" height="50" width="100">
                    <b><br>CA-7</b>
                </td>
                <td align="center" height="50" width="100">
                    <b><br> Programming Lab</b>
                </td>
                <td align="center" height="50" width="100">
                    <b><br>1200 Sq.Ft.b>
                </td>
                <td align="center" height="50" width="100">
                    <b><br>30 Students</b>
                </td>
                <td align="center" height="50" width="100">
                    <b><br>I5/500GB/DVDRW/18.5 TFT/HP3330PC/ Operating System-Windows 8</b>
                </td>

            </tr>


            <tr>
                </td>
                <td align="center" height="50" width="100">
                    <b><br>Smart Class Room</b>
                </td>
                <td align="center" height="50" width="100">
                    <b><br>SEMINAR/PRESENTATION</b>
                </td>
                <td align="center" height="50" width="100">
                    <b><br> 138.89 Sq.Ft.</b>b
                </td>
                <td align="center" height="50" width="100">
                    <b><br>90 Students</b>
                </td>
                <td align="center" height="50" width="100">
                    <b><br> Projector, Computer System, UPS, Mike, Fan, AC, Chair, Table, Podium</b>
                </td>

            </tr>


        </table>
    </div>
    </div>
    </div>
    </div>


    <br>
    <hr>
    <br>

    <section>
        <div class="vid">
            <iframe src="https://drive.google.com/file/d/1pYVeQY6-tKTVwGj0vxBLaPZQZHWtHydo/preview" width="1000px"
                height="450px" allow="autoplay"></iframe>
        </div>

        <br>

        <br>
        <div class="audio">
            <iframe src="https://drive.google.com/file/d/15Y_x6H2289wRMXhh0xEbBzdY2sXt_Hv3/preview" width="1002px"
                height="100px" allow="autoplay"></iframe>
        </div>

        <br>
        <br>
        <hr>
    </section>

    <section class="contact">
        <div class="last">
            <div class="col">

                <div class="last1">
                    <h3>About</h1>
                        <ul class="l1">

                            <li><a href="https://www.iul.ac.in/About/Overview/Overview.aspx"
                                    target="_blank">OVERVIEW</a></li>
                            <li><a href="https://iul.ac.in/About/Overview/Visionandmission.aspx" target="_blank">VISION,
                                    MISSION & OBJECTIVES</a></li>
                            <li><a href="https://iul.ac.in/achievements.aspx" target="_blank">AWARDS & ACHIEVEMENTS</a>
                            </li>
                            <li><a href="https://iul.ac.in/AdmissionInfo/Vertual_Tour.aspx#target"
                                    target="_blank">CAMPUS VIRTUAL TOUR</a></li>
                            <li><a href="https://iul.ac.in/About/leadership/Chancellor.aspx"
                                    target="_blank">LEADERSHIP</a></li>


                        </ul>
                </div>

                <div class="last1">
                    <h3>Academic</h3>
                    <ul class="l1">

                        <li><a href="https://iul.ac.in/Academic_Calendar.aspx"target="_blank">ACADEMIC CALENDAR</a></li>
                        <li><a href="https://iul.ac.in/exam/index.aspx"target="_blank">EXAMINATIONS</a></li>
                        <li><a href="https://iul.ac.in/Mooc.aspx"target="_blank">MOOCs</a></li>
                        <li><a href="https://iul.ac.in/BasicSkillCourses.aspx"target="_blank">BASIC SKILL COURSES</a></li>



                    </ul>
                </div>

                <div class="last1">
                    <h3>Faculties</h3>
                    <ul class="l1">

                        <li><a href="https://iul.ac.in/Department/Agriculture.aspx"target="_blank">
                                AGRICULTURAL SCIENCE & TECHNOLOGY</a></li>
                        <li><a href="https://iul.ac.in/Department/Engineering.aspx"target="_blank">ENGINEERING & IT</a></li>
                        <li><a href="https://iul.ac.in/Department/HealthMedical%20Sciences.aspx"target="_blank">HEALTH & MEDICAL
                                SCIENCES</a></li>
                        <li><a href="https://iul.ac.in/Department/Education.aspx"target="_blank">EDUCATION</a></li>



                    </ul>
                </div>

                <div class="last1">
                    <h3>Contact Us</h3>

                    <li class="lm"> <a href="info@iul.ac.in"target="_blank">info@iul.ac.in</a></li>
                </div>


            </div>

        </div>
    </section>


</body>

</html>
