---
layout: page
title: cv
permalink: /cv/
# description: Online view of my Curriculum vitae, downloadable PDF available.
nav: true
nav_order: 5
---

<!-- <div class="row" style="margin-top: -8rem; margin-bottom: 4rem">
	<a class="ml-auto mr-2" href="/assets/pdf/example_pdf.pdf" target="_blank" style="color: var(--global-text-color) !important;">
	  <i class="fas fa-file-pdf" style="font-size: 3rem;"></i>
	</a>
</div> -->

<div class="cv">

	<!-- General -->

	<div class="card p-3">
		<h3 class="card-title">General</h3>
	      <table class="table table-sm table-borderless">
	          <tr>
				<td class="p-0 pr-2 text-right">
					<b>Full Name</b>
				</td>
				<td class="p-0 pl-2 text-left">
					{{ site.first_name }} {{ site.middle_name }} {{ site.last_name }}
				</td>
			</tr>
			<tr>
				<td class="p-0 pr-2 text-right">
					<b>Contact</b>
				</td>
				<td class="p-0 pl-2 text-left">
					<a href="mailto:{{ site.email | encode_email }}" title="email">{{ site.email }}</a>
				</td>
			</tr>
			<tr>
				<td class="p-0 pr-2 text-right">
					<b>Languages</b>
				</td>
				<td class="p-0 pl-2 text-left">
					Japanese (Native), English (Beginner)
				</td>
			</tr>
            <tr>
				<td class="p-0 pr-2 text-right">
					<b>Interests</b>
				</td>
				<td class="p-0 pl-2 text-left">
					Bioinformatics, Epigenetics, Data Science, Labolatory automation, 3D print, VR
				</td>
			</tr>
		</table>
	</div>

	<!-- About me -->

	<!-- <div class="card p-3">
		<h3 class="card-title">About Me</h3>
		<div class="card-text p-3">
		I’m an associate software engineer for the Metal as a Service team at Canonical, with a strong passion for computational physics, particularly focused on astronomy, exoplanetary science, and other space-based endeavours.
		<br/>
		I began programming in 2011 with Python, and have developed extensive programming experience that I used to great effect in my 2021 bachelors project ”Distinguishing Intermediate Mass Black Hole Mergers From Short Duration Glitches”, my 2022 Masters Project “Determining The Parameters of Exoplanetary Candidates From Transit Timing Variations”, and my career as software engineer.
		<br/>
		In 2020 I became a fellow of the Royal Astronomical Society and a member of the European Astronomical Society to further my interest and professional options, as I have a strong interest in astrophysics research.
		<br/>
		In February 2022 I joined the AiCore Training scheme to become an Ai & Data Engineer, to eventually pursue a career in software engineering.
		In July 2022 I graduated First class as Mphys (Hons) Physics, Astronomy, and Cosmology at Portsmouth University, which additionally granted me status as a member of the Institue of Physics.
		<br/>
		I am also a beginner learner of Japanese, having undertaken extracurricular language modules during my final year of university, with a long term goal of bilinguality.
		</div>
	</div> -->

	<!-- About my research -->

	<!-- <div class="card p-3">
		<h3 class="card-title">About Me</h3>
		<div class="card-text p-3">
            <p>
                I began programming in 2011 with Python, and have developed extensive programming experience that I used to great effect in my 2021 bachelors project ”Distinguishing Intermediate Mass Black Hole Mergers From Short Duration Glitches”, my 2022 Masters Project “Determining The Parameters of Exoplanetary Candidates From Transit Timing Variations”, and my career as software engineer.
            </p>
            <p>
                In 2020 I became a fellow of the Royal Astronomical Society and a member of the European Astronomical Society to further my interest and professional options, as I have a strong interest in astrophysics research.
            </p>
            <p>
                test
            </p>
		</div>
	</div> -->


	<!-- Experience -->

	<div class="card p-3">
		<h3 class="card-title">
            Experience
        </h3>
		<div>
			<ul class="card-text list-group list-group-flush">
				<li class="list-group-item">
					<div class="row">
						<div	 class="col-sm-2 abbr">
							<abbr class="badge">
								2024-04 - present
							</abbr>
						</div>
						<div class="col-xs-10 cl-sm-10 col-md mt-2 mt-md-0">
							<h4 class="title font-weight-bold ml-1 ml-md-4">
                                Bioinformatics Researcher
                            </h4>
							<ul class="items">
								<li>
									Daiichi-Sankyo Co., Ltd.
								</li>
							</ul>
						</div>
					</div>
				</li>
                <li class="list-group-item">
					<div class="row">
						<div class="col-sm-2 abbr">
							<abbr class="badge">
								2023
							</abbr>
						</div>
						<div class="col-xs-10 cl-sm-10 col-md mt-2 mt-md-0">
							<h4 class="title font-weight-bold ml-1 ml-md-4">
                                "Picmobi" (Finalists, Recipient of BIPROGY Award and TomyK Award)
                            </h4>
							<ul class="items">
                                <i>
                                    Division of University Corporate Relations, University of Tokyo
                                </i>
                                <li>
                                    The service allows users to simply take a photo of the desired items, and our system coordinates the delivery of the products to a nearby hub.
                                </li>
								<li>
									Developed a Web app, an image recognition system for identifying products, and a location tracking system using Raspberry Pi with GNSS sensor-based technology.
								</li>
							</ul>
						</div>
					</div>
				</li>
				<li class="list-group-item">
					<div class="row">
						<div class="col-sm-2 abbr">
							<abbr class="badge">
								2022
							</abbr>
						</div>
						<div class="col-xs-10 cl-sm-10 col-md mt-2 mt-md-0">
							<h4 class="title font-weight-bold ml-1 ml-md-4">
                                Research Assistant
                            </h4>
							<ul class="items">
                                <i>
                                    Tokyo University of Science
                                </i>
                                <br>
								<!-- <li>
									"研究支援員" - in Japanese
                                </li> -->
								<li>
									Molecular biological experiment (RNA-seq, ATAC-seq, CUT&Tag, WGS, Mouse maintainance)
                                </li>
                                <li>
                                    NGS analysis (RNA-seq, ATAC-seq, scRNA-seq, scATAC-seq, CUT&Tag, WGS)
								</li>
							</ul>
						</div>
					</div>
				</li>
                <li class="list-group-item">
					<div class="row">
						<div class="col-sm-2 abbr">
							<abbr class="badge">
								2022 - 2024
							</abbr>
						</div>
						<div class="col-xs-10 cl-sm-10 col-md mt-2 mt-md-0">
							<h4 class="title font-weight-bold ml-1 ml-md-4">
                                Teaching Assistant
                            </h4>
							<ul class="items">
                                <i>
                                    Tokyo University of Science
                                </i>
								<li>
									Bioinformatics
								</li>
                                <li>
                                    Python, Google Colabolatory
                                </li>
							</ul>
						</div>
					</div>
				</li>
                <li class="list-group-item">
					<div class="row">
						<div class="col-sm-2 abbr">
							<abbr class="badge">
								2022
							</abbr>
						</div>
						<div class="col-xs-10 cl-sm-10 col-md mt-2 mt-md-0">
							<h4 class="title font-weight-bold ml-1 ml-md-4">
                                "Mobile trash can"
                            </h4>
							<ul class="items">
                                <i>
                                    Division of University Corporate Relations, University of Tokyo
                                </i>
								<li>
									As a leader, developed a trash can that moves in response to voice.
								</li>
                                <li>
                                    Raspberry pi, ROS (Melodic), LiDAR (RPLIDAR), OpenCV, Docker
                                </li>
							</ul>
						</div>
					</div>
				</li>
				<li class="list-group-item">
					<div class="row">
						<div class="col-sm-2 abbr">
							<abbr class="badge">
								2020 - 2024
							</abbr>
						</div>
						<div class="col-xs-10 cl-sm-10 col-md mt-2 mt-md-0">
							<h4 class="title font-weight-bold ml-1 ml-md-4">
                                Bioinformatics Engineer - Amelieff
                            </h4>
							<ul class="items">
                                <i>
                                    Amelieff Corp.
                                </i>
                                <br/>
								<li>
									Linux, Python, R, AWS, Docker, Researching, NGS analysis (RNA-seq, scRNA-seq, ATAC-seq, scATAC-seq, ChIP-seq, CUT&RUN, Re-seq, GWAS, Metagenomics, Long-read sequencer)
								</li>
							</ul>
						</div>
					</div>
				</li>
				<li class="list-group-item">
					<div class="row">
						<div class="col-sm-2 abbr">
							<abbr class="badge">
								2021
							</abbr>
						</div>
						<div class="col-xs-10 cl-sm-10 col-md mt-2 mt-md-0">
							<h4 class="title font-weight-bold ml-1 ml-md-4">
                                Bioinformatics Researcher - University of Tokyo
                            </h4>
							<ul class="items">
                                <i>
                                    University of Tokyo
                                </i>
								<li>
									Research about single-cell tools.
								</li>
                                <li>
                                    Jupyter Notebook, Google Colabolatory, NGS, Single-cell genomics
                                </li>
							</ul>
						</div>
					</div>
				</li>
				<li class="list-group-item">
					<div class="row">
						<div class="col-sm-2 abbr">
							<abbr class="badge">
								2019 - 2020
							</abbr>
						</div>
						<div class="col-xs-10 cl-sm-10 col-md mt-2 mt-md-0">
							<h4 class="title font-weight-bold ml-1 ml-md-4">
                                iGEM 2020 (Silver Medal)
                            </h4>
							<ul class="items">
                                <i>
                                    International Genetically Engineered Machine Competition
                                </i>
								<li>
									Exploring the conversion of nicotine into useful substances using genetic engineering to create a "Nico-friendly" society and prevent ecological damage from cigarette butt litter by adding value to discarded materials.
								</li>
							</ul>
						</div>
					</div>
				</li>
				<li class="list-group-item">
					<div class="row">
						<div class="col-sm-2 abbr">
							<abbr class="badge">
								2019
							</abbr>
						</div>
						<div class="col-xs-10 cl-sm-10 col-md mt-2 mt-md-0">
							<h4 class="title font-weight-bold ml-1 ml-md-4">
                                iGEM 2019 (Bronze Medal)
                            </h4>
							<ul class="items">
                                <i>
                                    International Genetically Engineered Machine Competition
                                </i>
								<li>
									Investigating genetic combinations to enhance <i>E. coli</i> 's radiation resistance by studying Deinococcus radiodurans, with the aim of creating radiation-resistant bacteria.
								</li>
							</ul>
						</div>
					</div>
				</li>
            </ul>
		</div>
	</div>


	<!-- Education -->

	<div class="card p-3">
		<h3 class="card-title">
            Education
        </h3>
		<div>
			<ul class="card-text list-group list-group-flush">
				<li class="list-group-item">
					<div class="row">
						<div class="col-sm-2 abbr">
							<abbr class="badge">
								2022-04 - 2024-03
							</abbr>
						</div>
						<div class="col-xs-10 cl-sm-10 col-md mt-2 mt-md-0">
							<h4 class="title font-weight-bold ml-1 ml-md-4">
                                Master of Science and Technology in Applied Biological Science - Tokyo University of Science
                            </h4>
							<ul class="items">
    							<!-- <li>
									指導教官: 
								</li> -->
							</ul>
						</div>
					</div>
				</li>
				<li class="list-group-item">
					<div class="row">
						<div	 class="col-sm-2 abbr">
							<abbr class="badge">
								2018 - 2022
							</abbr>
						</div>
						<div class="col-xs-10 cl-sm-10 col-md mt-2 mt-md-0">
							<h4 class="title font-weight-bold ml-1 ml-md-4">
                                Bachelor of Science and Technology in Applied Biological Science - Tokyo University of Science
                            </h4>
							<ul class="items">
								<!-- <li>
									iGEM
								</li> -->
							</ul>
						</div>
					</div>
				</li>
				<li class="list-group-item">
					<div class="row">
						<div class="col-sm-2 abbr">
							<abbr class="badge">
								2014 - 2017
							</abbr>
						</div>
						<div class="col-xs-10 cl-sm-10 col-md mt-2 mt-md-0">
							<h4 class="title font-weight-bold ml-1 ml-md-4">
                                Sendai Daiichi High School
                            </h4>
							<ul class="items">
								<!-- <li>
                                    Miyagi
								</li> -->
							</ul>
						</div>
					</div>
				</li>
			</ul>
		</div>
	</div>



	<!-- Presentations -->

	<div class="card p-3">
		<h3 class="card-title">
            Presentations
        </h3>
		<div>
			<ul class="card-text list-group list-group-flush">
				<li class="list-group-item">
					<div class="row">
						<div class="col-xs-10 cl-sm-10 col-md mt-2 mt-md-0">
							<ul class="items">
								<li>
                                    Poster Presentations:
									<ol>
										<li>
											<u><b>Hattori, T.</b></u>*, Watanabe, T., Sasaki, E., Namekawa, S. H., Maezawa, S. Single-cell ATAC-seq reveals stage-specific gene regulatory landscape during mouse spermatogenesis.
                                            <br/>
                                            <i>シングルセルゲノミクス研究会2022; August 30-31 2022; みやこめっせ 第二展示場 (京都市)</i>
										</li>
                                        <li>
                                            <u><b>Hattori, T.</b></u>*, Watanabe, T., Sasaki, E., Namekawa, S. H., Maezawa, S. Single-cell ATAC-seq reveals stage-specific gene regulatory landscape during mouse spermatogenesis.
                                            <br/>
                                            <i>総合研究院データサイエンス医療研究部門・核酸創薬研究部門　合同シンポジウム; September 2022; 東京理科大学 葛飾キャンパス図書館大ホール</i>
                                        </li>
                                        <li>
                                            <u><b>Hattori, T.</b></u>, Watanabe, T., Sasaki, E., Namekawa, S. H., Maezawa, S.* "マウス精⼦形成過程における分化運命決定機構の解明"
                                            <br>
                                            <i>NGS EXPO 2022; October 18-19, 2022; Osaka International Convention Center</i>
                                        </li>
                                        <li>
                                            <u><b>Hattori, T.</b></u>*, Watanabe, T., Sasaki, E., Namekawa, S. H., Maezawa, S. Single-cell ATAC-seq reveals stage-specific gene regulatory landscape during mouse spermatogenesis.
                                            <br/>
                                            <i>The International Symposium "Totipotency and Germ Cell Development"; November 23-25, 2022; Centennial Hall Kyusyu University School of Medichine, Fukuoka, Japan</i>
                                        </li>
                                        <li>
                                            Sugiyama R., Otsuka K., <u><b>Hattori T.</b></u>, Tatara M., Araki K., Iizuka M., Nakata I., Iguchi T., Masai H., Namekawa, S. H., Maezawa, S.* Dynamic nuclear lamina-chromatin interactions during spermatogenesis.
                                            <br/>
                                            <i>The International Symposium "Totipotency and Germ Cell Development"; November 23-25, 2022; Centennial Hall Kyusyu University School of Medichine, Fukuoka, Japan</i>
                                        </li>
                                        <li>
                                            <u><b>Hattori, T.</b></u>*, Watanabe, T., Sasaki, E., Namekawa, S. H., Maezawa, S. Single-cell ATAC-seq reveals stage-specific gene regulatory landscape during mouse spermatogenesis.
                                            <br>
                                            <i>The 45th Annual Meeting of the Molecular Biology Society of Japan; 2P-069; November 30 - December 2, 2022; Makuhari Messe International Exhibition Hall</i>
                                        </li>
                                        <li>
                                            Sugiyama R., Otsuka K., <u><b>Hattori T.</b></u>, Tatara M., Araki K., Iizuka M., Nakata I., Iguchi T., Masai H., Namekawa, S. H., Maezawa, S.* Dynamic nuclear lamina-chromatin interactions during spermatogenesis.
                                            <br>
                                            <i>The 45th Annual Meeting of the Molecular Biology Society of Japan; 2P-566; November 30 - December 2, 2022; Makuhari Messe International Exhibition Hall</i>
                                        </li>
                                        <li>
                                            <u><b>Hattori, T.</b></u>*, Sugiyama, R., Watanabe, T., Sasaki, E., Namekawa, S. H., Maezawa, S. Single-cell ATAC-seq reveals stage-specific gene regulatory landscape during mouse spermatogenesis.
                                            <br/>
                                            <i>総合研究院データサイエンス医療研究部門・デジタルトランスフォーメーション研究部門　合同シンポジウム; October 14, 2023; 東京理科大学 野田キャンパス7号館講堂</i>
                                        </li>
                                        <li>
                                            <u><b>Hattori, T.</b></u>*, Sugiyama, R., Watanabe, T., Sasaki, E., Namekawa, S. H., Maezawa, S. Single-cell ATAC-seq reveals stage-specific gene regulatory landscape during mouse spermatogenesis.
                                            <br>
                                            <i>The 14th International Workshop on Advanced Genomics (14AGW); October 4-6, 2023; Hitotsubashi Hall, National Center of Science Building</i>
                                        </li>
                                        <li>
                                            <u><b>Hattori, T.</b></u>*, Sugiyama, R., Watanabe, T., Sasaki, E., Namekawa, S. H., Maezawa, S. Single-cell ATAC-seq reveals stage-specific gene regulatory landscape during mouse spermatogenesis.
                                            <br>
                                            <i>NGS EXPO 2023; November 15-16, 2023; Osaka International Convention Center</i>
                                        </li>
                                        <li>
                                            <u><b>Hattori, T.</b></u>*, Sugiyama, R., Watanabe, T., Sasaki, E., Namekawa, S. H., Maezawa, S. Single-cell ATAC-seq reveals the important role of transcription factor SOX4 during mouse spermatogenesis.
                                            <br>
                                            <i>The 46th Annual Meeting of the Molecular Biology Society of Japan; December 6-8, 2023; Kobe International Conference Center, Kobe International Exhibition Hall, Kobe Portopia Hotel</i>
                                        </li>
                                        <li>
                                            <u><b>Hattori, T.</b></u>, Sugiyama, R., Watanabe, T., Sasaki, E., Namekawa, S. H., Maezawa, S.* Single-cell ATAC-seq reveals stage-specific gene regulatory landscape during mammalian spermatogenesis.
                                            <br>
                                            <i>The 46th Annual Meeting of the Molecular Biology Society of Japan; December 6-8, 2023; Kobe International Conference Center, Kobe International Exhibition Hall, Kobe Portopia Hotel</i>
                                        </li>
                                        <li>
                                            <u><b>Hattori, T.</b></u>*, Sugiyama, R., Watanabe, T., Sasaki, E., Namekawa, S. H., Maezawa, S. Single-cell ATAC-seq reveals stage-specific gene regulatory landscape during mouse spermatogenesis.
                                            <br>
                                            <i>PAGS拡大班会議; December 25-26, 2023; Yokohama</i>
                                        </li>
									</ol>
								</li>
								<br>
								<li>
                                    Oral Presentations:
                                    <ol>
                                        <li>
                                            <u><b>Hattori, T.</b></u>*, Watanabe, T., Sasaki, E., Namekawa, S. H., Maezawa, S. Single-cell ATAC-seq reveals stage-specific gene regulatory landscape during mouse spermatogenesis.
                                            <br>
                                            <i>The 45th Annual Meeting of the Molecular Biology Society of Japan; Workshop(2AW-15-3); November 30 - December 2, 2022; Makuhari Messe International Exhibition Hall</i>
                                        </li>
                                        <li>
                                            <u><b>Hattori, T.</b></u>*, Watanabe, T., Sasaki, E., Namekawa, S. H., Maezawa, S. Single-cell ATAC-seq reveals stage-specific gene regulatory landscape during mouse spermatogenesis.
                                            <br>
                                            <i>The 45th Annual Meeting of the Molecular Biology Society of Japan; Science Pitch(2SP-21-02); November 30 - December 2, 2022; Makuhari Messe International Exhibition Hall</i>
                                        </li>
                                        <li>
                                            Sugiyama R., Otsuka K., <u><b>Hattori T.</b></u>, Tatara M., Araki K., Iizuka M., Nakata I., Iguchi T., Masai H., Namekawa, S. H., Maezawa, S.* Dynamic nuclear lamina-chromatin interactions during spermatogenesis.
                                            <br>
                                            <i>The 45th Annual Meeting of the Molecular Biology Society of Japan; Workshop(2PW-15-4); November 30 - December 2, 2022; Makuhari Messe International Exhibition Hall</i>
                                        </li>
                                        <li>
                                            <u><b>Hattori, T.</b></u>*, Watanabe, T., Sasaki, E., Namekawa, S. H., Maezawa, S. マウス精子形成過程における分化運命決定機構の解明
                                            <br>
                                            <i>NGS 発生生物学現場の会 2022; December 7, 2022; 基礎生物学研究所</i>
                                        </li>
                                        <li>
                                            <u><b>Hattori, T.</b></u>*, Sugiyama, R., Watanabe, T., Sasaki, E., Namekawa, S. H., Maezawa, S. Single-cell ATAC-seq reveals stage-specific gene regulatory landscape during mouse spermatogenesis.
                                            <br>
                                            <i>NGS EXPO 2023; November 15-16, 2023; Osaka International Convention Center</i>
                                        </li>
                                        <li>
                                            <u><b>Hattori, T.</b></u>*, Otsuka K., Sugiyama, R., Watanabe, T., Sasaki, E., Namekawa, S. H., Maezawa, S. Single-cell ATAC-seq reveals stage-specific gene regulatory landscape during mouse spermatogenesis.
                                            <br>
                                            <i>生殖ライフスパン若手の会; November 29 - December 1, 2023; Nagoya</i>
                                        </li>
                                        <li>
                                            <u><b>Hattori, T.</b></u>*, Sugiyama, R., Watanabe, T., Sasaki, E., Namekawa, S. H., Maezawa, S. Single-cell ATAC-seq reveals the important role of transcription factor SOX4 during mouse spermatogenesis.
                                            <br>
                                            <i>The 46th Annual Meeting of the Molecular Biology Society of Japan; Science Pitch; December 6-8, 2023; Kobe International Conference Center, Kobe International Exhibition Hall, Kobe Portopia Hotel</i>
                                        </li>
                                        <li>
                                            <u><b>Hattori, T.</b></u>, Sugiyama, R., Watanabe, T., Sasaki, E., Namekawa, S. H., Maezawa, S.* Single-cell ATAC-seq reveals the important role of transcription factor SOX4 during mouse spermatogenesis.
                                            <br>
                                            <i>The 46th Annual Meeting of the Molecular Biology Society of Japan; Workshop (2P-151); December 6-8, 2023; Kobe International Conference Center, Kobe International Exhibition Hall, Kobe Portopia Hotel</i>
                                        </li>
									</ol>
								</li>
							</ul>
						</div>
					</div>
				</li>
			</ul>
		</div>
	</div>


	<!-- Skills -->

	<div class="card p-3">
		<h3 class="card-title">
            Skills
        </h3>
	      <table class="table table-sm table-borderless">
	          <tr>
				<td class="p-0 pr-2 text-right">
					<b>Programming</b>
				</td>
				<td class="p-0 pl-2 text-left">
					Python, R, Bash
				</td>
			</tr>
			<tr>
				<td class="p-0 pr-2 text-right">
					<b>Tools</b>
				</td>
				<td class="p-0 pl-2 text-left">
					Docker, Jupyter, Linux, Git & GitHub, Firebase, Fusion 360, Inkscape, Figma, Canva
				</td>
			</tr>
			<tr>
				<td class="p-0 pr-2 text-right">
					<b>Libraries</b>
				</td>
				<td class="p-0 pl-2 text-left">
					Python : Pandas, NumPy, Matplotlib, Seaborn, PyTorch, Scikit-learn
                    <br/>
                    R : tidyverse, related to bioinformatics
				</td>
			</tr>
			<tr>
				<td class="p-0 pr-2 text-right">
					<b>Others</b>
				</td>
				<td class="p-0 pl-2 text-left">
					Raspberry Pi, 3D printer, Oculus Quest 2, Drones
				</td>
			</tr>
		</table>
	</div>
</div>