<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title> Our Team </title>
  <style>
    body {
      	font-family: Calibri, sans-serif; 
        margin: 0;
        padding: 0;
    }

    header {
            background-color: #0FB784;
            color: #fff;
            text-align: center;
	    margin-top: 5px;
	    padding: 20px;
            position: relative;
    }

    #logo {
            position: absolute;
            left: 30px;
            top: 65%; 
            transform: translateY(-50%); 
            width: 100px;
            height: auto; 
            border-radius: 50%;
        }

    h1 {
            margin-right: -20px; 
            display: inline-block; 
            word-spacing: 10px; 
        }

    .team-member {
	    box-sizing: border-box;
	    padding: 10px;
            min-height: 100px;
            width: 25%;
            float: left;
        }

    .team-member img {
            width: 50%; 
            height: auto;
            border-radius: 50%;
	   }
  
     nav {
            background-color: #108769;
            color: #fff;
            text-align: center;
            padding: 10px;
            position: fixed;
            width: 100%;
            top: 0;
        }

      nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 20px;
        }



      .row { overflow: hidden; }

    /* Set the container width */
     .container {
      	    width: 90%; /* Adjust as needed */
            margin: auto; /* Center the container */
            text-align: center
        }

    /* Clear the float to ensure proper wrapping */    
    .row::after {
            content: "";
            display: table;
            clear: both;
        }
  </style>
</head>
<body>
   <header>
        <img id="logo" src="planet express.png" alt="Logo">
        <h1>Planet Express Team</h1>
    </header>

    <nav>
        <a href="#">Back to Earth</a>
        <a href="#">Missions</a>
        <a href="#">Contact</a>
    </nav>


  <div class="container">
    <!-- First Row -->
    <div class="row">
      <section class="team-member">
        <img src="professor_farnsworth 4.jpg" alt="Team Member 1">
        <h2> Professor Hubert J. Farnsworth</h2>
      </section>
      <section class="team-member">
        <img src="Fry.jfif" alt="Team Member 2">
        <h2>Philip J.Fry </h2>
      </section>
      <section class="team-member">
        <img src="turanga-leela 1.png" alt="Team Member 3">
        <h2>Turanga Leela</h2>
      </section>
      <section class="team-member">
        <img src="bender 2.jpg" alt="Team Member 4">
        <h2>Bender Bending Rodríguez</h2>
      </section>
    </div>

    <!-- Second Row -->
    <div class="row">
      <section class="team-member">
	<p>"Good news, everyone!" </p>
	<p> Self-described mad scientist - creator of courier service Planet Express. Senile, amoral, deranged and unpredictable old man with a gift for creating doomsday devices and atomic supermen. He has put at least one parallel universe in peril with his inventions and visited dozens more.</p>
      </section>
      <section class="team-member">
	<p>"Shut up and take my money!"</p>
        <p> Lazy, gullible, and none-too-bright delivery boy of Planet Express, a pro at getting into stupid situations. Despite his below-average intelligence, has a soft and tender heart, frequently going the extra mile to help his friends, even if he is oblivious to their problems.</p>
      </section>
      <section class="team-member">
	<p>"One of us is gonna have one eye"</p>
	<p> One-eyed mutant commander and pilot of Planet Express. Dreams of a happy family - looking for the ideal man, but every time idealizes one too much. Sometimes she does not notice that there are people nearby who sincerely love her for who she is.</p>
      </section>
      <section class="team-member">
	<p>"Bite my shiny metal ass!"</p>
	<p>Cigar-smoking, alcoholic and kleptomaniac designated in-universe as Bending Unit 22, unit number 1,729, serial number 2716057. Сonstantly trying to gain attention, apparently to maintain his already over-inflated ego. Mean-spirited, selfish nature, tending to constant abuse robot and Fry's best friend.</p>
    </section>
    </div>

    <!-- Third Row -->
    <div class="row">
      <section class="team-member">
        <img src="Amy_Wong 2.jpg" alt="Team Member 5">
        <h2> Ami Wong Ph.D.</h2>
      </section>
      <section class="team-member">
        <img src="hermes-conrad 1.jpg" alt="Team Member 6">
        <h2> Hermes Conrad </h2>
      </section>
      <section class="team-member">
        <img src="Dr Zoidberg 2.jpg" alt="Team Member 7">
        <h2>Dr. John A.Zoidberg</h2>
      </section>
      <section class="team-member">
        <img src="Scruffy 3.jpg" alt="Team Member 8">
        <h2>Scruffy Scruffington</h2>
      </section>
    </div>

    <!-- Fourth Row -->
    <div class="row">
      <section class="team-member">
 	<p>"Ok Fry, we're done putting on the bra!"</p>
	<p> Limited and slangy intern of Planet Express, who is kept on the team because she shares the same blood type as Professor Farnsworth. Dresses provocatively to spite her parents. Has a doctorate in applied physics. Swears in Cantonese dialect of Chinese.</p>  </section>  <section class="team-member">
 	<p> "Sweet freak of Mozambique!" </p>
	<p> Grade 34 Jamaican bureaucrat and accountant at Planet Express. He is afraid to make mistakes, as this may demote him to a lower grade. Represented Jamaica at the Olympics as "a world-class limboer", is said to be the only man to win Gold Medals in both limbo and sex...</p> </section>   <section class="team-member">	<p> "Woop Woop Woop!"</p>	<p> Decapodian, a crustacean-like species of alien, staff doctor of Planet Express. Has woeful understanding of human physiology and questionable credentials. Extremely poor despite his profession, implied to be frequently homeless when not at work. Not kosher, speaks a Yiddish-inflected accent.</p>  </section> <section class="team-member">
	<p> "Yup."</p>
	<p> Lazy and profound janitor of Planet Express. Refers to himself in the third person. Spends time reading an edition of National Pornographic. Nobody remembers his name or ever seeing him before. Owns 40,000 shares of Planet Express, more than anyone else, because he strongly believes in the company.</p>  </section>
    </div>
  </div>
</body>
</html>
