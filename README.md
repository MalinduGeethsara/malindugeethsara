<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Malindu Geethsara | Portfolio</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    },
                    colors: {
                        github: {
                            bg: '#0d1117',
                            border: '#30363d',
                            text: '#c9d1d9',
                            accent: '#58a6ff',
                            secondaryAccent: '#30A3DC'
                        }
                    }
                }
            }
        }
    </script>
    <style>
        body {
            background-color: #0d1117;
            background-image: radial-gradient(circle at top, rgba(88, 166, 255, 0.05) 0%, transparent 40%),
                              radial-gradient(circle at bottom right, rgba(48, 163, 220, 0.05) 0%, transparent 40%);
        }
        .icon-card:hover {
            box-shadow: 0 0 15px rgba(88, 166, 255, 0.2);
            border-color: rgba(88, 166, 255, 0.5);
            transform: translateY(-2px);
        }
    </style>
</head>
<body class="text-github-text antialiased min-h-screen flex flex-col items-center p-6 md:p-12">

<main class="max-w-4xl w-full space-y-20 mt-10">
        <section class="text-center space-y-6 animate-fade-in-up">
            <h1 class="text-4xl md:text-6xl font-bold text-white tracking-tight">
                Hi 👋, I'm Malindu Geethsara
            </h1>
            <h3 class="text-xl md:text-2xl text-gray-400 font-light">
                A passionate 
                <span class="font-semibold text-transparent bg-clip-text bg-gradient-to-r from-github-accent to-github-secondaryAccent">
                    Full Stack Developer
                </span> 
                from Sri Lanka
            </h3>
            
<div class="flex justify-center pt-4">
                <img src="https://komarev.com/ghpvc/?username=malindugeethsara&label=Profile%20views&color=0e75b6&style=flat" 
                     alt="Profile Views" 
                     class="rounded opacity-90 hover:opacity-100 transition-opacity" />
            </div>
        </section>
        <hr class="border-github-border w-1/3 mx-auto">
        <section class="space-y-8">
            <h2 class="text-2xl md:text-3xl font-semibold text-white text-center md:text-left flex items-center gap-2 justify-center md:justify-start">
                <span>🛠️</span> Languages and Tools
            </h2>
            
<div class="grid grid-cols-4 md:grid-cols-6 lg:grid-cols-9 gap-4">
                <div class="icon-card bg-white/5 border border-white/10 rounded-xl p-4 flex justify-center items-center transition-all duration-300 backdrop-blur-sm" title="HTML5">
                    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="HTML5" class="w-10 h-10 object-contain"/>
                </div>
                <div class="icon-card bg-white/5 border border-white/10 rounded-xl p-4 flex justify-center items-center transition-all duration-300 backdrop-blur-sm" title="CSS3">
                    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="CSS3" class="w-10 h-10 object-contain"/>
                </div>
                <div class="icon-card bg-white/5 border border-white/10 rounded-xl p-4 flex justify-center items-center transition-all duration-300 backdrop-blur-sm" title="JavaScript">
                    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="JavaScript" class="w-10 h-10 object-contain"/>
                </div>
                <div class="icon-card bg-white/5 border border-white/10 rounded-xl p-4 flex justify-center items-center transition-all duration-300 backdrop-blur-sm" title="TypeScript">
                    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" alt="TypeScript" class="w-10 h-10 object-contain"/>
                </div>
                <div class="icon-card bg-white/5 border border-white/10 rounded-xl p-4 flex justify-center items-center transition-all duration-300 backdrop-blur-sm" title="React">
                    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="React" class="w-10 h-10 object-contain"/>
                </div>
                <div class="icon-card bg-gray-200 border border-white/10 rounded-xl p-4 flex justify-center items-center transition-all duration-300 backdrop-blur-sm" title="Next.js">
                    <!-- Added gray bg for Next.js to make the black logo pop -->
                    <img src="https://cdn.worldvectorlogo.com/logos/nextjs-2.svg" alt="Next.js" class="w-10 h-10 object-contain"/>
                </div>
                <div class="icon-card bg-white/5 border border-white/10 rounded-xl p-4 flex justify-center items-center transition-all duration-300 backdrop-blur-sm" title="Tailwind CSS">
                    <img src="https://www.vectorlogo.zone/logos/tailwindcss/tailwindcss-icon.svg" alt="Tailwind" class="w-10 h-10 object-contain"/>
                </div>
                <div class="icon-card bg-white/5 border border-white/10 rounded-xl p-4 flex justify-center items-center transition-all duration-300 backdrop-blur-sm" title="Node.js">
                    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="Node.js" class="w-10 h-10 object-contain"/>
                </div>
                <div class="icon-card bg-gray-200 border border-white/10 rounded-xl p-4 flex justify-center items-center transition-all duration-300 backdrop-blur-sm" title="Express">
                    <!-- Added gray bg for Express to make black logo visible -->
                    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/express/express-original-wordmark.svg" alt="Express" class="w-10 h-10 object-contain"/>
                </div>
                <div class="icon-card bg-white/5 border border-white/10 rounded-xl p-4 flex justify-center items-center transition-all duration-300 backdrop-blur-sm" title="PHP">
                    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/php/php-original.svg" alt="PHP" class="w-10 h-10 object-contain"/>
                </div>
                <div class="icon-card bg-white/5 border border-white/10 rounded-xl p-4 flex justify-center items-center transition-all duration-300 backdrop-blur-sm" title="Java">
                    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="Java" class="w-10 h-10 object-contain"/>
                </div>
                <div class="icon-card bg-white/5 border border-white/10 rounded-xl p-4 flex justify-center items-center transition-all duration-300 backdrop-blur-sm" title="Python">
                    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="Python" class="w-10 h-10 object-contain"/>
                </div>
                <div class="icon-card bg-white/5 border border-white/10 rounded-xl p-4 flex justify-center items-center transition-all duration-300 backdrop-blur-sm" title="C++">
                    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" alt="C++" class="w-10 h-10 object-contain"/>
                </div>
                <div class="icon-card bg-white/5 border border-white/10 rounded-xl p-4 flex justify-center items-center transition-all duration-300 backdrop-blur-sm" title="MySQL">
                    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="MySQL" class="w-10 h-10 object-contain"/>
                </div>
                <div class="icon-card bg-white/5 border border-white/10 rounded-xl p-4 flex justify-center items-center transition-all duration-300 backdrop-blur-sm" title="MongoDB">
                    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" alt="MongoDB" class="w-10 h-10 object-contain"/>
                </div>
                <div class="icon-card bg-white/5 border border-white/10 rounded-xl p-4 flex justify-center items-center transition-all duration-300 backdrop-blur-sm" title="PostgreSQL">
                    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original-wordmark.svg" alt="PostgreSQL" class="w-10 h-10 object-contain"/>
                </div>
                <div class="icon-card bg-white/5 border border-white/10 rounded-xl p-4 flex justify-center items-center transition-all duration-300 backdrop-blur-sm" title="Git">
                    <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="Git" class="w-10 h-10 object-contain"/>
                </div>
                <div class="icon-card bg-white/5 border border-white/10 rounded-xl p-4 flex justify-center items-center transition-all duration-300 backdrop-blur-sm" title="Figma">
                    <img src="https://www.vectorlogo.zone/logos/figma/figma-icon.svg" alt="Figma" class="w-10 h-10 object-contain"/>
                </div>
            </div>
        </section>
        <hr class="border-github-border w-1/3 mx-auto">
        <section class="space-y-8">
            <h2 class="text-2xl md:text-3xl font-semibold text-white text-center md:text-left flex items-center gap-2 justify-center md:justify-start">
                <span>📊</span> GitHub Stats
            </h2>
            
<div class="flex flex-col md:flex-row gap-6 justify-center md:justify-start items-center">
                <img src="https://github-readme-streak-stats.herokuapp.com/?user=malindugeethsara&theme=transparent&hide_border=true&border_radius=6.5&stroke=c9d1d9&ring=58a6ff&fire=58a6ff&currStreakNum=c9d1d9&sideNums=c9d1d9&currStreakLabel=c9d1d9&sideLabels=c9d1d9&dates=c9d1d9" 
                     alt="GitHub Streak" 
                     class="max-w-full hover:scale-[1.02] transition-transform shadow-lg rounded-lg border border-github-border bg-black/20" />
                     
<img src="https://github-readme-stats.vercel.app/api?username=malindugeethsara&show_icons=true&locale=en&theme=transparent&bg_color=00000000&border_color=30363d&title_color=58a6ff&icon_color=58a6ff&text_color=c9d1d9" 
                     alt="GitHub Stats" 
                     class="max-w-full hover:scale-[1.02] transition-transform shadow-lg rounded-lg border border-github-border bg-black/20" />
            </div>
        </section>
        <hr class="border-github-border w-1/3 mx-auto">
        <section class="space-y-8 pb-20">
            <h2 class="text-2xl md:text-3xl font-semibold text-white text-center md:text-left flex items-center gap-2 justify-center md:justify-start">
                <span>🤝</span> Connect with me
            </h2>
            
<div class="flex flex-wrap justify-center md:justify-start gap-4">
                <a href="https://www.linkedin.com/in/malindu-geethsara-/" target="_blank" rel="noopener noreferrer" 
                   class="flex items-center gap-3 px-6 py-3 bg-[#0077B5] hover:bg-[#005e8e] text-white rounded-full font-medium transition-all hover:shadow-[0_0_15px_rgba(0,119,181,0.5)] hover:-translate-y-1">
                    <svg class="w-5 h-5 fill-current" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512">
                        <path d="M100.28 448H7.4V148.9h92.88zM53.79 108.1C24.09 108.1 0 83.5 0 53.8a53.79 53.79 0 0 1 107.58 0c0 29.7-24.1 54.3-53.79 54.3zM447.9 448h-92.68V302.4c0-34.7-.7-79.2-48.29-79.2-48.29 0-55.69 37.7-55.69 76.7V448h-92.78V148.9h89.08v40.8h1.3c12.4-23.5 42.69-48.3 87.88-48.3 94 0 111.28 61.9 111.28 142.3V448z"/>
                    </svg>
                    LinkedIn
                </a>
                <a href="https://portfolio-26-psi.vercel.app/" target="_blank" rel="noopener noreferrer" 
                   class="flex items-center gap-3 px-6 py-3 bg-[#255E63] hover:bg-[#1a4347] text-white rounded-full font-medium transition-all hover:shadow-[0_0_15px_rgba(37,94,99,0.5)] hover:-translate-y-1">
                    <svg class="w-5 h-5 fill-current" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512">
                        <path d="M352 256c0 22.2-1.2 43.6-3.3 64H163.3c-2.2-20.4-3.3-41.8-3.3-64s1.2-43.6 3.3-64h185.4c2.2 20.4 3.3 41.8 3.3 64zm28.8-64H503.9c5.3 20.5 8.1 41.9 8.1 64s-2.8 43.5-8.1 64H380.8c2.1-20.6 3.2-42 3.2-64s-1.1-43.4-3.2-64zm112.6-32H376.7c-10-63.9-29.8-117.4-55.3-151.6c78.3 20.7 142 77.5 171.9 151.6zm-149.1 0H167.7c6.1-36.4 15.5-68.6 27-94.7c10.5-23.6 22.2-40.7 33.5-51.5C239.4 3.2 248.7 0 256 0s16.6 3.2 27.8 13.8c11.3 10.8 23 27.9 33.5 51.5c11.6 26 20.9 58.2 27 94.7zm-209 0H18.6C48.6 85.9 112.4 29.1 190.6 8.4C165.1 42.6 145.3 96.1 135.3 160zM8.1 192H131.2c-2.1 20.6-3.2 42-3.2 64s1.1 43.4 3.2 64H8.1C2.8 299.5 0 278.1 0 256s2.8-43.5 8.1-64zM194.7 446.6c-11.6-26-20.9-58.2-27-94.6H344.3c-6.1 36.4-15.5 68.6-27 94.6c-10.5 23.6-22.2 40.7-33.5 51.5C272.6 508.8 263.3 512 256 512s-16.6-3.2-27.8-13.8c-11.3-10.8-23-27.9-33.5-51.5zM135.3 352c10 63.9 29.8 117.4 55.3 151.6C112.4 482.9 48.6 426.1 18.6 352H135.3zm358.1 0c-29.9 74.1-93.6 130.9-171.9 151.6c25.5-34.2 45.2-87.7 55.3-151.6H493.4z"/>
                    </svg>
                    Portfolio
                </a>
                <a href="mailto:gamalindugeethsara@gmail.com" 
                   class="flex items-center gap-3 px-6 py-3 bg-[#D14836] hover:bg-[#a53627] text-white rounded-full font-medium transition-all hover:shadow-[0_0_15px_rgba(209,72,54,0.5)] hover:-translate-y-1">
                    <svg class="w-5 h-5 fill-current" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512">
                        <path d="M48 64C21.5 64 0 85.5 0 112c0 15.1 7.1 29.3 19.2 38.4L236.8 313.6c11.4 8.5 27 8.5 38.4 0L492.8 150.4c12.1-9.1 19.2-23.3 19.2-38.4c0-26.5-21.5-48-48-48H48zM0 176V384c0 35.3 28.7 64 64 64H448c35.3 0 64-28.7 64-64V176L294.4 339.2c-22.8 17.1-54 17.1-76.8 0L0 176z"/>
                    </svg>
                    Email Me
                </a>
                
</div>
    </section>
        
</main>

</body>
</html>
