# myresume
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>my-resume</title>
    <style>
        body{
            padding: 30px;
        }
        h2{
            text-align: center;
        }
        .top{
            justify-content: space-between;
            display: flex;
        }
        .onep{
            margin-left: 50px;
        }
        table{
            border-collapse: collapse;
            width: 96%;
            margin: 30px;
        }
        th,td{
            border: 1px solid black;
            padding: 10px;
            text-align: center;
        }
        table.thover td:hover {  
            transform: translateY(-10px);
            background-color:rgba(245, 245, 245, 0.584);
            transition: transform 0.2s ease-in-out;
        }
        table.thover th:hover {  
            transform: translateY(-10px);
            background-color:rgba(245, 245, 245, 0.584);
            transition: transform 0.2s ease-in-out;
        }
        .twop{
            margin-left: 30px;
        }
        .pro{
            margin: 30px;
        }
        .pd{
            height: 150px;
            width: 370px;
            display: flex;
            align-items: right;
            justify-content: space-around;
        }
        .twop:hover {  
            transform: translateX(10px);
            background-color:rgba(245, 245, 245, 0.584);
            transition: transform 0.2s ease-in-out;
        }
        .pro:hover {  
            transform: translateX(10px);
            background-color:rgba(245, 245, 245, 0.584);
            transition: transform 0.2s ease-in-out;
        }
    </style>
</head>

<body>
    <h2>RESUME</h2>
    <div class="top">
        <div class="right">
            <h4>Tamide Kishore</h4>
        </div>
        <div class="left">
            <p>Email:tamidekishore7@gmail.com</p>
            <p>Cell :+916309695195</p>
        </div>
    </div>
    <hr color="black">

    <h3><u>CAREER OBJECTIVES:</u></h3>
    <p class="onep">To work with best of my abilities and skills in order to benefit my organization to be better other in this
    competitive time an influential position in the organization. </p>

    <H3><u>EDUCATIONAL QUALIFICATIONS:</u></H3>
    <!-- <div class="thover"> -->
        <table class="thover">
            <tr>
                <th>Group</th>
                <th>Board/University</th>
                <th>Institute College</th>
                <th>Percentage(%)</th>
            </tr>
            <tr>
                <td>B.sc-MECS(year-2022)</td>
                <td>Sri Krishna Devaraya University, Anantapur</td>
                <td>Sri Sai Baba National degree college, Anantapur</td>
                <td>86%</td>
            </tr>
            <tr>
                <td>M.P.C</td>
                <td>Board of Intermediate Education, Andhra Pradesh</td>
                <td>Sri Chaitanya junior college, Anantapur</td>
                <td>82%</td>
            </tr>
            <tr>
                <td>S.S.C</td>
                <td>Secondary School for Education, Andhra Pradesh</td>
                <td>Sri Saraswathi vidyanikethan High School, Anantapur</td>
                <td>79</td>
            </tr>
        </table>
    <!-- </div> -->

    <H3><u>TECHNICAL SKILLS:</u></H3>
    <P class="twop">❖ SQL</P>
    <P class="twop">❖ JAVA</P>
    <P class="twop">❖ HTML and CSS</P>

    <H3><u>OTHER ACTIVITIES</u></H3>
    <P class="twop">❖Participated in Pradhan Mantri Kaushal Yojana Vikas (Pmkvy) and completed training on courses i.e.M.S Office.</P>

    <H3><u>STRENGTHS:</u></H3>
    <P class="twop">❖Hard Working</P>
    <P class="twop">❖Positive Thinking</P>

    <H3><u>PROJECT:</u></H3>
    <p class="pro">❖Interfacing LCD with 8051 Microcontroller</p>

    <h3><u>HOBBIES:</u></h3>
    <P class="twop">❖Playing cricket,watching movies,Reading books and Drawing.</P>

    <H3><u>PERSONAL DETAILS:</u></H3>
    <div class="pd">
        <div>
            <P>Father name    :</P>
            <p>Mother name    :</p>
            <p>Date of Birth  :</p>
            <p>Languages Known:</p>
            <p>Address        :</p>
        </div>
        <div>
            <p>T.Sreenivasulu</p>
            <p>T.Prabhavathi</p>
            <p>08/01/01</p>
            <p>Telugu and English</p>
            <p>D.No:6-1-19,Azad Nagar,Anantapur.</p>
        </div>
        
    </div>
</body>
</html>
