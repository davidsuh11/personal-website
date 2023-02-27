<style lang='postcss'>
    div {
        font-size: 28px;
    }
    body {
        //overflow: hidden;
    }
    ::-webkit-scrollbar {
        width: 5px;
    }
    ::-webkit-scrollbar-track {
        background: #2e2e2e;
    }   
    ::-webkit-scrollbar-thumb {
        background: #888;
    }
    ::-webkit-scrollbar-thumb:hover {
        background: #555;
    }
</style>
<body>
    <div class='grid p-10 grid-cols-7'> 
        <div class='col-span-2 overflow-hidden sticky top-5 h-screen hidden lg:block'>
            <p class='text-xl'>David Suh</p> <br>
            <p class='text-xs'>Hello!</p>
        </div>
        <div class='col-span-5 overflow-hidden px-2'>
            <h1 class='text-xl font-bold'>📖 Education </h1>
            <p class='float-right text-sm'> 2020-2024 </p>
            <p>University of Chicago </p> 
            <p class='text-xs'> M.S. Computer Science, <br>
            B.A. Computer Science, <br>
            B.A. Mathematics <br> </p>
            <br>
            <h1 class='text-xl font-bold'>🏢 Work Experience </h1>
            <p class='float-right text-sm' > Jan. 2023 - Present</p>
            <p class='text-sm'>Computer Vision Engineering Intern</p>
            <p class='text-sm'>@EdLight PBC</p>
            <hr class='my-1'>
            <p class='text-xs'>Developed a browser based document scanning system utilizing computer vision techniques. Existing market solution SDKs and a
                homebrew CNN combined using a SqueezeNet backbone were used to amplify detection performance and accuracy to >90%.
                Further improved computational performance through implementation with TensorFlow Lite to provide users a real time edge
                preview of documents. This was then wrapped into a React.JS component. </p>
            <br>
            <p class='float-right text-sm' > Jan. 2023 - Present</p>
            <p class='text-sm'>Advanced Research Assistant</p>
            <p class='text-sm'>@Voltage Research Group, UChicago</p>
            <hr class='my-1'>
            <p class='text-xs'>Worked as a research assistant in maintain and developing research related software and tools, including the maintenance and
                migration of the research group’s website using Django, react, and other data visualization tools such d3. Furthermore,
                implemented an optimized data pipeline uploaded papers and implemented an optimized segment tree system for searching. </p>
            <br>
            <p class='float-right text-sm' > Summer 2018, 2019</p>
            <p class='text-sm'>Data Science Intern</p>
            <p class='text-sm'>@Yonsei Graduate School of Civil Engineering</p>
            <hr class='my-1'>
            <p class='text-xs'>Assisted researchers (M.S, Ph.D students) in research concerning the utilization of machine learning in the realm of civil engineering.
                Included wrangling data into usable form for machine learning purposes through R and pandas, as well as optimizing the
                distributed computation system through Hadoop for faster training.</p>
            <br>
            <h1 class='text-xl font-bold'>🏆 Competitions/Extracurriculars</h1>
            <p class='text-sm'>2023 Citadel Datathon Midwest Regional</p>
            <p class='text-sm'>🥇1st Place</p>
            <hr class='my-1'>
            <p class='text-xs'>Came in first in the Midwest Regional for Citadel’s 2023 Datathon. Winning paper was written on the environmental (and
            consequently health-related) effects of greenspaces and bluespaces, in particular on surface temperatures and air quality index
            through programmatic time series analysis, using metrics such as the Dicky-Fuller test, and providing strong evidence of data
            correlation through K-means segmentation and heuristic minima discovery. Winning prize money was $10,000 for the team. <a class='text-xs' href='https://github.com/yashgupta-7/datathon-s23'> Link to code</a>. <a class='text-xs' href='https://drive.google.com/file/d/1aEdz-22jrZ1jjw8eJmYRWBIcfrMINVoP/view?usp=sharing'> Download writeup</a>.</p>
            <br>
            <p class='text-sm'>2022 University of Chicago Mathematics Research Experience for Undergrads (REU)</p>
            <p class='text-sm'>Paid Full Program Attendee</p>
            <hr class='my-1'>
            <p class='text-xs'> Attended the UChicago Mathematics REU, a competitive program for undergraduates to spend 8 weeks emulating the graduate
                mathematics research process under the supervision of a mentor. The final paper, Mean Field Games and Weak Solutions, written on
                the topic of stochastic mean field games, a natural topic that forms from optimal control of the Fokker-Planck equation, which
                concerns the optimization of the actions of a small agent compared to a large population. </p>
            <br>
            <p class='text-sm'>2022 William Lowell Putnam Math Competition</p>
            <p class='text-sm'>75th percentile score (9/120)</p>
            <hr class='my-1'>
            <p class='text-xs'> Scored a 9/120 on the 2022 Putnam Exam, a score which is just under the top 1000, about the 75th percentile overall. For reference, the typical median score on this competition is 0, and the mean is usually 1 or 2.</p>
        </div>
    </div>
</body>
