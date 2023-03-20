<script>
    import { CodeSnippet, Accordion, AccordionItem, OutboundLink, InlineNotification } from "carbon-components-svelte";
</script>
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
    <div class='grid p-10 grid-cols-5 lg:grid-cols-7 items-start mx-24'> 
        <div class='px-4 col-span-2 overflow-hidden sticky top-5 h-screen hidden lg:block'>
            <p class='text-5xl font-bold'>David Suh</p> <br>
            <p class='text-lg'>My name is David Suh. I was born in Austin, Texas on December 17, 2001. After attending school until first grade while my dad completed his PhD, our family returned to South Korea for a while. While there, I attened Seoul International School from Grade 1 through 12. During this time, I would slowly but surely discover my passion for programming and mathematical thinking. I participated in a number of tournaments at the national/international level, such NAQT, IYPT/KYPT, Empire mock trial, and more. I was accepted into the University of Chicago in 2020. The first year I attended remotely from Korea, and for the second year onwards I have attended in person. I am currently a Mathematics and Computer Science major, and I am also part of the joint Masters program in Computer Science, thus I am also purusing a MS in Computer Science at the moment. My personal interests are in optimization, probabilistic algorithms, and machine learning. In my free time I go to the gym and play video games.</p>
        </div>
        <div class='col-span-5 overflow-hidden px-2'>
            <h1 class='text-3xl font-bold'>📖 Education </h1>
            <p class='float-right text-xl'> 2020-2024 </p>
            <p class='text-2xl'>University of Chicago </p> 
            <div>
                <p class='text-lg'> M.S. Computer Science, <br>
                    B.A. Computer Science, <br>
                    B.A. Mathematics <br> </p>
            </div>
            
            <Accordion align='start' size='sm'>
                <AccordionItem title='Relevant Coursework'>
                    <p class='underline'>Graduate/Ph.D Level Coursework is noted with a *:</p>
                    <p>Honors Real Analysis*, Probability Theory (acc.), Honors Algebra*, Networks,
                    Machine Learning*, Computer Vision, Honors Theory of Algorithms, Honors Combinatorics* <br><br>
                    </p>             
                </AccordionItem>
            </Accordion>


            <br>
            <h1 class='font-bold'>🏢 Work Experience </h1>
            <p class='float-right text-xl' > Jan. 2023 - Present</p>
            <p class='text-xl'>Computer Vision Engineering Intern</p>
            <p class='text-xl'>@Edlight, PBC</p>

            <hr class='my-1'>
            <p class='text-base'>Developed a browser based document scanning system utilizing computer vision techniques. Existing market solution SDKs and a
                homebrew CNN combined using a SqueezeNet backbone were used to amplify detection performance and accuracy to >90%.
                Further improved computational performance through implementation with TensorFlow Lite to provide users a real time edge
                preview of documents. This was then wrapped into a React.JS component. </p>
            <br>
            <p class='float-right text-xl' > Jan. 2023 - Present</p>
            <p class='text-xl'>Advanced Research Assistant</p>
            <p class='text-xl'>@Voltage Research Group, UChicago</p>
            <hr class='my-1'>
            <p>Worked as a research assistant in maintain and developing research related software and tools, including the maintenance and
                migration of the research group’s website using Django, react, and other data visualization tools such d3. Furthermore,
                implemented an optimized data pipeline uploaded papers and implemented an optimized segment tree system for searching. </p>
            <br>
            <p class='float-right text-xl' > Summer 2018, 2019</p>
            <p class='text-xl'>Data Science Intern</p>
            <p class='text-xl'>@Yonsei Graduate School of Civil Engineering</p>
            <hr class='my-1'>
            <p>Assisted researchers (M.S, Ph.D students) in research concerning the utilization of machine learning in the realm of civil engineering.
                Included wrangling data into usable form for machine learning purposes through R and pandas, as well as optimizing the
                distributed computation system through Hadoop for faster training.</p>
            <br>
            <h1 class='text-3xl font-bold'>🏆 Competitions/Extracurriculars</h1>
            <p class='text-xl'>2023 Citadel Datathon Midwest Regional</p>
            <p class='text-lg'>🥇1st Place</p>
            <hr class='my-1'>
            <p>Came in first in the Midwest Regional for Citadel’s 2023 Datathon. Winning paper was written on the environmental (and
            consequently health-related) effects of greenspaces and bluespaces, in particular on surface temperatures and air quality index
            through programmatic time series analysis, using metrics such as the Dicky-Fuller test, and providing strong evidence of data
            correlation through K-means segmentation and heuristic minima discovery. Winning prize money was $10,000 for the team. <OutboundLink type='outbound' href='https://github.com/yashgupta-7/datathon-s23'>Link to code.</OutboundLink> <OutboundLink href='https://drive.google.com/file/d/1aEdz-22jrZ1jjw8eJmYRWBIcfrMINVoP/view?usp=sharing'> Download writeup.</OutboundLink ></p>
            <br>
            <p class='text-xl'>2022 University of Chicago Mathematics Research Experience for Undergrads (REU)</p>
            <p class='text-lg'>Paid Full Program Attendee</p>
            <hr class='my-1'>
            <p> Attended the UChicago Mathematics REU, a competitive program for undergraduates to spend 8 weeks emulating the graduate
                mathematics research process under the supervision of a mentor. The final paper, Mean Field Games and Weak Solutions, written on
                the topic of stochastic mean field games, a natural topic that forms from optimal control of the Fokker-Planck equation, which
                concerns the optimization of the actions of a small agent compared to a large population. </p>
            <br>
            <p class='text-xl'>2022 William Lowell Putnam Math Competition</p>
            <p class='text-lg'>75th percentile score (9/120)</p>
            <hr class='my-1'>
            <p> Scored a 9/120 on the 2022 Putnam Exam, a score which is just under the top 1000, about the 75th percentile overall. For reference, the typical median score on this competition is 0, and the mean is usually 1 or 2.</p>
        </div>
    </div>
</body>
