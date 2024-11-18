<html>
<head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>People</title>
    <style>
		.people-container {
			max-width: 1200px;
			margin: 0 auto;
			padding: 20px;
		}

		.people-grid {
			display: flex;
			flex-wrap: wrap;
			gap: 3rem 4rem;
			justify-content: center;
			padding: 1rem;
		}

		.person-card {
			flex: 0 1 280px;
			max-width: 280px;
			margin-bottom: 1rem;
			/* Add vertical offset to every other card */
			transform: translateY(0);
			transition: transform 0.3s ease;
		}

		/* Offset every other card */
		.person-card:nth-child(even) {
			transform: translateY(2rem);
		}

		/* Offset every third card a different amount */
		.person-card:nth-child(3n) {
			transform: translateY(1rem);
		}

		.headshot {
			display: block;
			width: 200px;
			height: 200px;
			border-radius: 50%;
			margin: 5px 0;
		}

		.role {
			font-size: 18px;
			line-height: 1.3;
		}

		.role-description {
			font-size: 14px;
			margin-top: 0.5rem;
		}

		.alumni-section {
			margin-top: 3rem;
			width: 100%;
			transform: none !important; /* Prevent offset on alumni section */
		}

		@media (max-width: 768px) {
			.people-grid {
				flex-direction: column;
				align-items: center;
				gap: 2rem;
			}

			.person-card {
				width: 100%;
				max-width: 100%;
				text-align: center;
				/* Remove vertical offset on mobile */
				transform: translateY(0) !important;
			}

			.headshot {
				margin: 5px auto;
			}
		}
    </style>
</head>
<body>
    <div class="people-container">
        <div class="people-grid">
            <!-- Principal Investigator -->
            <div class="person-card">
                <h2>Jesse Gomez PH.D.</h2>
                <img class="headshot" src="/assets/img/jesse.jpg" alt="photo of jesse gomez">
                <div class="role">
                    <b>Principal Investigator</b>
                    <div class="role-description">
                        jessegomez [at] princeton [dot] edu<br>
                        PNI Room 234<br>
                        Jesse Gomez is a neuroscientist in the Princeton Neuroscience Institute where he
                        is the principal investigator of the Brain Development Lab. He received his BA in
                        Neuroscience from Dartmouth College with Dr. Brad Duchaine, his PhD in
                        Neuroscience from Stanford University with Dr. Kalanit Grill-Spector, and
                        completed postdoctoral training at UC Berkeley with Dr. Kevin Weiner. At Princeton,
                        he teaches courses on Developmental and Cognitive Neuroscience.
                    </div>
                </div>
            </div>

            <!-- Postdoctoral Scholar -->
            <div class="person-card">
                <h2>Toshikazu "Toshi" Miyata</h2>
                <img class="headshot" src="/assets/img/toshi.png" alt="photo of Toshi Miyata">
                <div class="role">
                    <b>Postdoctoral Scholar</b>
                    <div class="role-description">
                        Dr. Toshi Miyata is a joint NINS-Princeton research fellow between the Gomez Lab and the <a href="https://www.nips.ac.jp/scbm/en/" target="_blank">Takemura Lab</a> of the National Institute for Physiological Sciences in Okazaki, Japan. He is an expert in diffusion MRI and is researching how white matter connectivity scaffolds the spatial and temporal organization of the human brain across development.
                    </div>
                </div>
            </div>

            <!-- Research Specialist -->
            <div class="person-card">
                <h2>Anna Lyn Williams</h2>
                <img class="headshot" src="/assets/img/anna.jpg" alt="photo of anna lyn williams">
                <div class="role">
                    <b>Research Specialist</b>
                    <div class="role-description">
                        Anna is a predoctoral research specialist at the Princeton Neuroscience Institute and lab manager of the Brain Development Lab. Currently, her research focuses on characterizing patterns of cortical folding in the human dorsal visual stream, as well as examining the corresponding neural and behavioral development of visuospatial attention. She is also interested in applying quantitative magnetic resonance imaging (qMRI) to examine how fine-scale changes in tissue composition and macromolecular volume relate to maturing visual abilities. 
                    </div>
                </div>
            </div>

            <!-- Graduate Students -->
            <div class="person-card">
                <h2>Frederick d'Oleire Uquillas</h2>
                <img class="headshot" src="/assets/img/fred.jpg" alt="photo of frederick uquillas">
                <div class="role">
                    <b>Graduate Student</b>
                    <div class="role-description">
                        Frederick is a Presidential Fellow and PhD candidate in the Neuroscience Department at Princeton University. His research focuses on large scale brain networks and cerebellar contributions to cortical structure and function across the lifespan, and is supported by the National Science Foundation and National Academies of Sciences, Engineering and Medicine.
                    </div>
                </div>
            </div>

            <div class="person-card">
                <h2>Omar Singleton</h2>
                <img class="headshot" src="/assets/img/omar.jpg" alt="photo of omar singleton">
                <div class="role">
                    <b>Graduate Student</b>
                    <div class="role-description">
                        Omar Singleton is a PhD student at the Princeton Neuroscience Institute. He previously worked on neuroimaging projects at
                        MGH, and now studies how the human thalamus develops across the lifespan and the roles
                        it plays in mediating developmental changes in the cortex in neurotypical individuals 
                        and those diagnosed with psychiatric disorders.
                    </div>
                </div>
            </div>

            <div class="person-card">
                <h2>Priscilla Louis</h2>
                <img class="headshot" src="/assets/img/priscilla.jpg" alt="photo of mariam latif">
                <div class="role">
                    <b>Graduate Student</b>
                    <div class="role-description">
                        Priscilla is studying under Jesse Gomez and Tim Buschman at the Princeton Neuroscience Institute. Supported by the Presidential Fellowship, she seeks to understand the structural and functional development of working memory, episodic memory, and their overlapping networks in humans.
                    </div>
                </div>
            </div>

            <div class="person-card">
                <h2>Edan Daniel</h2>
                <img class="headshot" src="/assets/img/edan.jpg" alt="photo of edan daniel">
                <div class="role">
                    <b>Graduate Student</b>
                    <div class="role-description">
                        Edan is a PhD student at the Princeton Neuroscience Institute. She previously worked on EEG analyses in the Dinstein
                        Lab at Ben-Gurion University in Israel, and now researches how visual experience
                        during either childhood or adulthood shapes the organization and computations 
                        that occur within visual cortex.
                    </div>
                </div>
            </div>

            <div class="person-card">
                <h2>Patricia Hoyos</h2>
                <img class="headshot" src="/assets/img/patricia.jpg" alt="photo of patricia hoyos">
                <div class="role">
                    <b>Graduate Student</b>
                    <div class="role-description">
                        Patricia Hoyos is a PhD candidate at the Princeton Neuroscience Institute, and member of the Gomez and Kastner labs. She is currently studying the development of the human dorsal stream to understand how changes in our attentional abilities and biases are shaped by structural and computational changes occurring within visual cortex. Patricia is also an HHMI Gilliam Fellow and Presidential Fellow.
                    </div>
                </div>
            </div>

            <div class="person-card">
                <h2>Damola Ogunlade</h2>
                <img class="headshot" src="/assets/img/damola.jpg" alt="photo of damola ogunlade">
                <div class="role">
                    <b>Graduate Student</b>
                    <div class="role-description">
                        Damola completed her undergraduate degree in neuroscience at the University of 
                        Pennsylvania. She is a first-year student in PNI rotating in the lab where she'll be
                        studying auditory cortex development through novel MRI methods.
                    </div>
                </div>
            </div>

            <div class="person-card">
                <h2>Bing Li</h2>
                <img class="headshot" src="/assets/img/bing.png" alt="photo of bing li">
                <div class="role">
                    <b>Graduate Student</b>
                </div>
            </div>

            <!-- Alumni Section -->
            <div class="alumni-section">
                <h2>Lab Alumni</h2>
                <p>
                    Ruggaya Musa<br>
                    Mariam Latif<br>
                    Rowen Gesue<br>
                    Carlos Cortez<br>
                    Folarin Okulaja<br>
                    Sidney Gregorek<br>
                    Zach Yazdani<br>
                    Matthew Trotter<br>
                    Stuart Duffield<br>
                    Allie Reynolds<br>
                    Niranjana Bienkowska<br>
                    Shannon Chen
                </p>
            </div>
        </div>
    </div>
</body>
</html>