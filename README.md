<!DOCTYPE html>
<html>
	<head>
		<meta charset="utf-8" />
		<link rel="stylesheet" href="reservia.css"/>
		<link rel="preconnect" href="https://fonts.gstatic.com">
		<link href="https://fonts.googleapis.com/css2?family=Raleway&display=swap" rel="stylesheet">
		<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.13.1/css/all.min.css" /> <!--permet d'ajouter les icônes-->
		<title>Reservia</title>
	</head>

	<body>
		<header>
			<p><img src="images/logo/Reservia.svg" alt="Reservia" class= "titre"></p>
				<ul>
					<li><a href="#Hébergements">Hébergements</a></li><!--Hébergements et activités ancres menant aux sections-->
					<li><a href="#Activités">Activités</a></li>
					<li>S'inscrire</li>
				</ul>
		</header>

		<nav>
			<h2>Trouvez votre hébergement pour des vacances de rêve</h2>
			<p>En plein centre ville ou en pleine nature </p>

			<form method="post" action="traitement.php">
				<div class="rechercher">
					<i class="fas fa-map-marker-alt"></i>
					<input type="search" placeholder="Marseille, France" class="champs_recherche" /><input type="submit" value="Rechercher" class="bouton_rechercher" />
				</div>
				<br/>
				<div class="filtres">
						<p>Filtres</p>
						<div class="cash"><i class="fas fa-money-bill"></i><input type="button" value="Economique" class="money"></div>
						<div class="child"><i class="fas fa-child"></i><input type="button" value="Familial" class="famille"></div>
						<div class="heart"><i class="fas fa-heart"></i><input type="button" value="Romantique" class="romantique"></div>
						<div class="dog"><i class="fas fa-dog"></i><input type="button" value="Animaux autorisés" class="animaux"></div>
				</div>
			</form>
			<br/>
			<div class="info"><i class="fas fa-info-circle"></i>Plus de 500 logements sont disponibles dans cette ville</div><br/>
		
		</nav>
		<section>
			<div id="hébergements">
				<h2>Hébergements à Marseille</h2>
				<div id="logements"> 
					<figure id="cannebière">
						<a href="" target="blank"><img src="images/hebergements/4_small/marcus-loke-WQJvWU_HZFo-unsplash.jpg" alt="Auberge de la Cannebière" >
						<figcaption id="cannebière_text">
							Auberge de la Cannebière
						</figcaption>
						<figcaption id="prixC">
							Nuit à partir de 25€ 
						</figcaption>
						<figcaption id="stars">
							<i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star stars_blank"></i>
						</figcaption>
						</a>
					</figure>

					<figure id="port">
						<a href="" target="blank"><img src="images/hebergements/4_small/fred-kleber-gTbaxaVLvsg-unsplash.jpg" alt="Hôtel du Port">
						<figcaption id="port_text">
							Hôtel du Port
						</figcaption>
						<figcaption id="prixP">
							Nuit à partir de 52€
						</figcaption>
						<figcaption id="starsP">
							<i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i>
						</figcaption>
						</a>
					</figure>

					<figure id="mouettes">
						<a href="" target="blank"><img src="images/hebergements/4_small/reisetopia-B8WIgxA_PFU-unsplash.jpg" alt="Hôtel les Mouettes">
						<figcaption id="mouettes_text">
							Hôtel les Mouettes
						</figcaption>
						<figcaption id="prixM">
							Nuit à partir de 76€
						</figcaption>
						<figcaption id="starsM">
							<i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star stars_blank" id></i>	
						</figcaption>
						</a>
					</figure>

					<figure id="mer">
						<a href="" target="blank"><img src="images/hebergements/4_small/annie-spratt-Eg1qcIitAuA-unsplash.jpg" alt="Hôtel de la mer">
						<figcaption id="mer_text">
							Hôtel de la mer
						</figcaption>
						<figcaption id="prixMer">
							Nuit à partir de 46€
						</figcaption>
						<figcaption id="starsMer">
							<i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star stars_blank"></i><i class="fas fa-star stars_blank"></i>
						</figcaption>
						</a>
					</figure>

					<figure id="panier">
						<a href="" target="blank"><img src="images/hebergements/4_small/nicate-lee-kT-ZyaiwBe0-unsplash.jpg" alt="Auberge le Panier">
						<figcaption id="panier_text">
							Auberge Le Panier
						</figcaption>
						<figcaption id="prixPanier">
							Nuit à partir de 23€
						</figcaption>
						<figcaption id="starspanier">
							<i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star stars_blank"></i>
						</figcaption>
						</a>
					</figure>

					<figure id="amina">
						<a href="" target="blank"><img src="images/hebergements/4_small/febrian-zakaria-M6S1WvfW68A-unsplash.jpg" alt="Hôtel chez Amina">
						<figcaption id="amina_text">
							Hôtel chez Amina
						</figcaption>
						<figcaption id="prixA">
							Nuit à partir de 96€
						</figcaption>
						<figcaption id="starsA">
							<i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i>
						</figcaption>
						</a>
					</figure>
				</div>
				<div id="afficher"><a href="" target="blank">Afficher plus</a></div>
			</div>
			<aside>
				<div id="populaires">
				<h3>Les plus populaires <i class="fas fa-chart-line"></i></h3>
					<div id="pop">
						<a href="" target="blank">
							<figure id="soleil">
								<figcaption id="text_soleil">
									<img src="images/hebergements/4_small/emile-guillemot-Bj_rcSC5XfE-unsplash.jpg" alt="Hôtel Le soleil du matin">
									<div id="text_sun">
										<h3>Hôtel Le soleil du matin</h3>
										<p>Nuit à partir de 128€</p><br/>
										<div id="starsS">
											<i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i>
										</div>
									</div>
								</figcaption>
							</figure>
						</a>	

						<a href="" target="blank">
							<figure id="eau">
								<figcaption id="text_eau">
									<img src="images/hebergements/4_small/aw-creative-VGs8z60yT2c-unsplash.jpg" alt="Au coeur de l'eau chambres d'hôtes">
									<div id="text_water">
										<h3>Au coeur de l'eau Chambres d'hôtes</h3>
										<p>	Nuit à partir de 71€</p><br/>
										<div id="starsE">
											<i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star stars_blank_b"></i>
										</div>
									</div>
								</figcaption>
							</figure>
						</a>

						<a href="" target="blank">
							<figure id="blanc">
								<figcaption id="text_blanc">
									<img src="images/hebergements/4_small/febrian-zakaria-sjvU0THccQA-unsplash.jpg" alt="Hôtel tout bleu et blanc">
									<div id="text_white">
										<h3>Hôtel Tout bleu et Blanc</h3>
										<p>Nuit à partir de 68€</p><br/>
										<div id="starsB">
											<i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star stars_blank_b"></i>
										</div>	
									</div>
								</figcaption>
							</figure>
						</a>	
					</div>
				</div>
			</aside>
		</section>

		<article>
			<h2>Activités à Marseille</h2>
			<div id="Activités">

				<a href="" target="blank">
					<figure id="Vieux_port">
						<figcaption id="Vieux_port_text">
						<img src="images/activites/4_small/reno-laithienne-QUgJhdY5Fyk-unsplash.jpg" alt="Vieux Port">
						<h3>Vieux Port</h3>
						</figcaption>
					</figure>
				</a>

				<div id="fort_iles">
				<a href="" target="blank">
					<figure id="Fort">
						<figcaption id="Fort_text">
						<img src="images/activites/4_small/paul-hermann-QFTrLdQIRhI-unsplash.jpg" alt="Fort de Pomègues">
						<h3>Fort de Pomègues</h3>
						</figcaption>
					</figure>
				</a>

				<a href="" target="blank">
					<figure id="Iles">
						<figcaption id="Iles_text">
						<img src="images/activites/4_small/kevin-hikari-rV_Qd1l-VXg-unsplash.jpg" alt="Iles du Frioul">
						<h3>Iles du Frioul</h3>
						</figcaption>
					</figure>
				</a>
				</div>

				<a href="" target="blank">
					<figure id="calanques">
						<figcaption id="calanques_text">
						<img src="images/activites/4_small/kilyan-sockalingum-NR8-cBCN3aI-unsplash.jpg" alt="Parc National des Calanques">
						<h3>Parc National des Calanques</h3>
						</figcaption>
					</figure>
				</a>

				<div id="garde_longchamp">
				<a href="" target="blank">
					<figure id="Garde">
						<figcaption id="garde_text">
						<img src="images/activites/4_small/florian-wehde-xW9e8gdotxI-unsplash.jpg" alt="Notre Dame de la Garde">
						<h3>Notre-Dame-de-la-Garde</h3>
						</figcaption>
					</figure>
				</a>

				<a href="" target="blank">
					<figure id="Longchamp">
						<figcaption id="longchamp_text">
						<img src="images/activites/4_small/lena-paulin-wH2-EJoDcV0-unsplash.jpg" alt="Parc Longchamp">
						<h3>Parc Longchamp</h3>
						</figcaption>
					</figure>
				</a>
				</div>
			</div>
		</article>
		
		<footer>
			<ul>
				<li><h3>A propos</h3></li>
				<li><a href="#">Fonctionnement du site</a></li>
				<li><a href="#">Conditions générales de vente</a></li>
				<li><a href="#">Données et confidentialité</a></li>
			</ul>

			<ul>
				<li><h3>Nos hébergements</h3></li>
				<li><a href="#">Charte qualité</a></li>
				<li><a href="#">Soumettre votre hôtel</a></li>
			</ul>

			<ul>
				<li><h3>Assistance</h3></li>
				<li><a href="#">Centre d'aide</a></li>
				<li><a href="#">Nous contacter</a></li>
			</ul>
		</footer>

	</body>
</html>
