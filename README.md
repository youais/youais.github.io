<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Yiwei Chai</title>

  <style>
    body {
      margin: 0;
      padding: 40px;
      font-family: Arial, sans-serif;
      background: #0d1117;
      color: #c9d1d9;
    }

    /* Main container */
    .github-layout {
      display: grid;
      grid-template-columns: 1fr 3fr; /* 1 : 3 ratio */
      gap: 32px;
      max-width: 1200px;
      margin: auto;
    }

    /* Left column */
    .sidebar {
      background: #161b22;
      padding: 24px;
      border-radius: 12px;
      text-align: center;
    }

    .profile-pic {
      width: 160px;
      height: 160px;
      border-radius: 50%;
      object-fit: cover;
      border: 4px solid #30363d;
      margin-bottom: 20px;
    }

    .username {
      font-size: 24px;
      font-weight: bold;
      margin-bottom: 8px;
    }

    .bio {
      color: #8b949e;
      font-size: 14px;
      line-height: 1.5;
    }

    /* Right column */
    .content {
      background: #161b22;
      padding: 32px;
      border-radius: 12px;
    }

    .content h1 {
      margin-top: 0;
      color: #58a6ff;
    }

    .content p {
      line-height: 1.7;
      color: #c9d1d9;
    }

    /* Mobile responsive */
    @media (max-width: 768px) {
      .github-layout {
        grid-template-columns: 1fr;
      }
    }
  </style>
</head>

<body>

  <div class="github-layout">

    <!-- Left Column -->
    <aside class="sidebar">
      <img
        class="profile-pic"
        src="https://avatars.githubusercontent.com/u/9919?v=4"
        alt="Profile Picture"
      />

      <div class="username">octocat</div>

      <div class="bio">
        Full-stack developer <br />
        Open source enthusiast <br />
        Building cool things on GitHub
      </div>
    </aside>

    <!-- Right Column -->
    <main class="content">
      <h1>About</h1>

      <p>
        This right-hand section can contain repositories, README content,
        project descriptions, contribution history, markdown-rendered text,
        or any other GitHub-style information.
      </p>

      <p>
        The layout uses CSS Grid with a 1:3 width ratio:
        the left sidebar occupies 1 fraction unit,
        while the main content occupies 3 fraction units.
      </p>

      <p>
        On smaller screens, the layout automatically stacks into a single column.
      </p>
    </main>

  </div>

</body>
</html>




# Yiwei Chai

<br>

<b> Exoplanet Atmospheres | Comparative --> Populations </b>

Hello! I’m Yiwei Chai, a PhD student at Johns Hopkins University. I study exoplanets and their systems using a variety of observational methods. I am interested in using comparative studies to place planets into context, particularly as we move towards tackling population-level questions about the nature of other worlds in our Galaxy.

My current projects involve the atmospheric characterisation of a multiple sub-Neptune system with JWST, and the development of end-to-end simulations to predict transiting exoplanet atmosphere science yields for the upcoming Nancy Grace Roman Space Telescope. I also occasionally dabble in the spectroscopy of young directly-imaged giant planets.

Previously, I have investigated the dynamical interactions and spectral composition of a debris disk-brown dwarf system using JWST's MIRI MRS ([paper here](https://iopscience.iop.org/article/10.3847/1538-4357/ad74f4)), and tested ways to quantify model comparison for exoplanet atmospheres through Bayesian evidence calibration.

You can view my CV [here](./yiwei_cv_grad_20260303.pdf) (current as of 3/3/26).

When I'm not doing research, I enjoy reading novels, ice skating, rock climbing, and catering to the whims of my cats, Ozzie and Oolong.

<br>

This site is a work-in-progress, so stay tuned for further details!
