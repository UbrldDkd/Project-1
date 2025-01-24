<!doctype html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Project N1</title>
    <style>
      a:link {
        color: white;
        background-color: transparent;
        text-decoration: none;
      }
      a:visited {
        color: yellow;
        background-color: transparent;
        text-decoration: underline;
      }
      a:hover {
        color: tan;
        background-color: transparent;
        text-decoration: none;
      }
      #spcid {
        margin: 10px;
        color: white;
        border: 2px solid black;
        padding: 10px;
      }
      h1 {
        background-color: tan;
        border: 3px solid white;
        padding: 10px;
      }
      .center {
        text-align: center;
      }
    </style>
  </head>
  <body style="background-color: darkred;">
    <h1>Project N1</h1>

    <p style="color: white; text-align: center;">This is an example.</p>
    <hr>
    <p style="color: darkred; text-align: justify;">This is my social page</p>

    <!-- Link to Instagram -->
    <a href="https://www.instagram.com/im_rotting_from_the_inside_out/" target="_blank">Instagram</a>

    <hr>
    <p style="text-align: center; color: black;">
      <i><mark>This is an example.</mark></i>
    </p>

    <pre>
      Bonnie lies across the ocean
      Bonnie lies across the sea
      Bonnie lies across the ocean
      Oh, bring back my Bonnie to me.
    </pre>

    <p style="text-align: left; color: black; background-color: tan;">
      <b>This is an example.</b>
    </p>

    <!-- Image Example -->
    <img src="./Image.jpg" alt="2000s Baddie" width="220px">

    <p style="font-size: 40px;">
      <del>Irwmune <sub>sakutari</sub> <sup>tavis</sup></del>
    </p>

    <p><bdo dir="rtl">This</bdo> may be an <q><abbr title="Apple">Example</abbr></q></p>

    <h1>This text has a white border</h1>

    <!-- Styled paragraph with internal CSS -->
    <p id="spcid">This paragraph is styled with internal CSS.</p>
    <p>This paragraph is normal</p>

    <!-- Button to redirect to Instagram -->
    <button onclick="window.location.href = 'https://www.instagram.com/im_rotting_from_the_inside_out/'">
      This is another link to my socials
    </button>

    <p style="text-align: justify;">
      The <small>quick</small> <em>brown</em> fox jumps <sup>over</sup> the lazy <b>dog</b>. This is a sample text for alignment testing and layout design.
    </p>

    <hr style="color:tan">

    <!-- Center-align Click the Cherry Text and Image -->
    <div class="center">
      <p>Click the <span style="color:red">Cherry</span></p>
      <a href="page-2.html">
        <img src="pixel-art-cherries-cherries.gif" alt="Cherry" style="width:40px;height:44px;">
      </a>
    </div>
  </body>
</html>

