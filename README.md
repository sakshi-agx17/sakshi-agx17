<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sakshi's Journey Timeline</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            padding: 40px 20px;
            min-height: 100vh;
        }

        .container {
            max-width: 900px;
            margin: 0 auto;
            background: rgba(255, 255, 255, 0.95);
            padding: 50px 40px;
            border-radius: 20px;
            box-shadow: 0 20px 60px rgba(0, 0, 0, 0.3);
        }

        h1 {
            text-align: center;
            font-size: 3em;
            font-weight: 900;
            letter-spacing: 8px;
            margin-bottom: 20px;
            color: #1a1a1a;
        }

        .subtitle {
            text-align: center;
            font-size: 1.3em;
            color: #555;
            margin-bottom: 60px;
            font-weight: 500;
        }

        .timeline {
            position: relative;
            padding: 20px 0;
        }

        .timeline::before {
            content: '';
            position: absolute;
            left: 50%;
            transform: translateX(-50%);
            width: 4px;
            height: 100%;
            background: linear-gradient(180deg, #667eea 0%, #764ba2 100%);
            border-radius: 2px;
        }

        .timeline-item {
            position: relative;
            margin-bottom: 80px;
            display: flex;
            align-items: center;
        }

        .timeline-item:last-child {
            margin-bottom: 0;
        }

        .left-content, .right-content {
            width: 45%;
            padding: 20px;
        }

        .left-content {
            text-align: right;
            padding-right: 40px;
        }

        .right-content {
            text-align: left;
            padding-left: 40px;
        }

        .timeline-badge {
            position: absolute;
            left: 50%;
            transform: translateX(-50%);
            width: 70px;
            height: 70px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 2em;
            font-weight: bold;
            color: white;
            z-index: 2;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.2);
            border: 5px solid rgba(255, 255, 255, 0.95);
        }

        .badge-1 { background: linear-gradient(135deg, #f093fb 0%, #f5576c 100%); }
        .badge-2 { background: linear-gradient(135deg, #4facfe 0%, #00f2fe 100%); }
        .badge-3 { background: linear-gradient(135deg, #43e97b 0%, #38f9d7 100%); }
        .badge-4 { background: linear-gradient(135deg, #fa709a 0%, #fee140 100%); }
        .badge-5 { background: linear-gradient(135deg, #30cfd0 0%, #330867 100%); }
        .badge-6 { background: linear-gradient(135deg, #a8edea 0%, #fed6e3 100%); }

        .dashed-line {
            position: absolute;
            width: 60px;
            height: 2px;
            background: repeating-linear-gradient(
                to right,
                #999 0px,
                #999 8px,
                transparent 8px,
                transparent 16px
            );
            top: 50%;
            transform: translateY(-50%);
        }

        .left-content .dashed-line {
            right: -30px;
        }

        .right-content .dashed-line {
            left: -30px;
        }

        .tag {
            display: inline-block;
            padding: 8px 20px;
            border-radius: 25px;
            font-weight: 700;
            font-size: 0.9em;
            margin-bottom: 10px;
            color: #1a1a1a;
        }

        .tag-orange { background: #ffd89b; }
        .tag-yellow { background: #ffeb99; }
        .tag-pink { background: #ffc3d4; }
        .tag-purple { background: #e0c3fc; }
        .tag-cyan { background: #a8edea; }
        .tag-green { background: #b8f5cd; }

        .year {
            font-size: 2.5em;
            font-weight: 900;
            margin-bottom: 15px;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
        }

        .description {
            font-size: 1em;
            line-height: 1.6;
            color: #333;
        }

        @media (max-width: 768px) {
            .container {
                padding: 30px 20px;
            }

            h1 {
                font-size: 2em;
                letter-spacing: 4px;
            }

            .subtitle {
                font-size: 1em;
            }

            .timeline::before {
                left: 35px;
            }

            .timeline-item {
                flex-direction: column;
                align-items: flex-start;
                padding-left: 80px;
            }

            .timeline-badge {
                left: 35px;
                width: 50px;
                height: 50px;
                font-size: 1.5em;
            }

            .left-content, .right-content {
                width: 100%;
                text-align: left;
                padding: 0;
                padding-left: 20px;
            }

            .dashed-line {
                display: none;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>TIMELINE</h1>
        <p class="subtitle">MY JOURNEY THROUGH TECH & GROWTH</p>
        
        <div class="timeline">
            <!-- Item 1 -->
            <div class="timeline-item">
                <div class="left-content">
                    <span class="tag tag-orange">Foundation</span>
                    <div class="year">2020</div>
                    <p class="description">Graduated high school with 90% marks. Failed JEE Mains by 4%. Enrolled in a government college in Bareilly.</p>
                    <div class="dashed-line"></div>
                </div>
                <div class="timeline-badge badge-1">1</div>
                <div class="right-content"></div>
            </div>

            <!-- Item 2 -->
            <div class="timeline-item">
                <div class="left-content"></div>
                <div class="timeline-badge badge-2">2</div>
                <div class="right-content">
                    <span class="tag tag-yellow">First Steps</span>
                    <div class="year">2021</div>
                    <p class="description">Started learning Python from YouTube tutorials. Built first ML model with 40% accuracy. Applied to internships and faced rejections.</p>
                    <div class="dashed-line"></div>
                </div>
            </div>

            <!-- Item 3 -->
            <div class="timeline-item">
                <div class="left-content">
                    <span class="tag tag-pink">Growth</span>
                    <div class="year">2022</div>
                    <p class="description">Started AddictoAlert project. Surveyed 300+ students. Applied statistical methods and built SVM models.</p>
                    <div class="dashed-line"></div>
                </div>
                <div class="timeline-badge badge-3">3</div>
                <div class="right-content"></div>
            </div>

            <!-- Item 4 -->
            <div class="timeline-item">
                <div class="left-content"></div>
                <div class="timeline-badge badge-4">4</div>
                <div class="right-content">
                    <span class="tag tag-purple">Validation</span>
                    <div class="year">2023</div>
                    <p class="description">Won C.S.T.U.P. Government Grant beating 150+ applicants. Published first research paper on nomophobia.</p>
                    <div class="dashed-line"></div>
                </div>
            </div>

            <!-- Item 5 -->
            <div class="timeline-item">
                <div class="left-content">
                    <span class="tag tag-cyan">Breakthrough</span>
                    <div class="year">2024</div>
                    <p class="description">Landed internship at Hum Technologies. Worked at Clairvoyant. Joined Ignite AI as ML Engineer. Got accepted to ASU.</p>
                    <div class="dashed-line"></div>
                </div>
                <div class="timeline-badge badge-5">5</div>
                <div class="right-content"></div>
            </div>

            <!-- Item 6 -->
            <div class="timeline-item">
                <div class="left-content"></div>
                <div class="timeline-badge badge-6">6</div>
                <div class="right-content">
                    <span class="tag tag-green">New Chapter</span>
                    <div class="year">2025</div>
                    <p class="description">Started MS in Computer Software Engineering at Arizona State University. Currently hustling for internships and building projects.</p>
                    <div class="dashed-line"></div>
                </div>
            </div>
        </div>
    </div>
</body>
</html>
