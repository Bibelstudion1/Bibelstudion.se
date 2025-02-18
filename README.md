<!DOCTYPE html>
<html lang="sv">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bibelstudion.se</title>

   

    <style>
        body {
            margin: 0;
            font-family: 'Inter', system-ui;
            background-color: #0a0a0a;
            color: #ffffff;
        }

        .top-bar {
            position: sticky;
            top: 0;
            background-color: #111111;
            color: #ffffff;
            font-size: 0.9rem;
            padding: 8px 20px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            z-index: 1000;
            border-bottom: 1px solid #2a2a2a;
        }

        .top-bar a {
            color: #ffffff;
            text-decoration: none;
            margin-right: 25px;
            font-size: 0.9rem;
            transition: opacity 0.3s ease;
        }

        .top-bar a:hover {
            opacity: 0.8;
            text-decoration: underline;
        }

        .header {
            position: sticky;
            top: 30px;
            background-color: #000000;
            padding: 15px 20px;
            border-bottom: 1px solid #2a2a2a;
            display: flex;
            align-items: center;
            justify-content: space-between;
            z-index: 999;
            overflow: hidden;
        }

        .logo {
            font-size: 2rem;
            font-weight: 700;
            color: #ffffff;
            display: flex;
            align-items: center;
            gap: 8px;
        }

        .logo span {
            color: #00ff88;
            font-weight: 700;
        }

        .search-bar {
            display: flex;
            align-items: center;
            flex: 1;
            margin: 0 40px;
            max-width: 600px;
        }

        .search-bar input {
            flex: 1;
            padding: 12px 20px;
            background: #1a1a1a;
            border: 1px solid #333333;
            border-radius: 30px;
            color: #ffffff;
            font-size: 1rem;
            transition: all 0.3s ease;
        }

        .search-bar input:focus {
            outline: none;
            border-color: #00ff88;
            box-shadow: 0 0 0 3px rgba(0, 255, 136, 0.1);
        }

        .search-bar button {
            padding: 12px 25px;
            background: linear-gradient(135deg, #00ff88, #00cc6a);
            border: none;
            color: #000000;
            font-weight: 600;
            border-radius: 30px;
            cursor: pointer;
            margin-left: -75px;
            transition: all 0.3s ease;
        }

        .search-bar button:hover {
            transform: scale(1.05);
            box-shadow: 0 5px 15px rgba(0, 255, 136, 0.2);
        }

        .user-actions {
            display: flex;
            align-items: center;
            gap: 25px;
        }

        .user-actions a {
            color: #ffffff;
            text-decoration: none;
            font-weight: 500;
            transition: color 0.3s ease;
        }

        .user-actions a:hover {
            color: #00ff88;
        }

        .nav-links {
            background-color: #1a1a1a;
            display: flex;
            justify-content: center;
            padding: 15px 0;
            border-bottom: 1px solid #2a2a2a;
            flex-wrap: wrap;
            gap: 15px;
        }

        .nav-links a {
            color: #ffffff;
            text-decoration: none;
            padding: 8px 15px;
            border-radius: 8px;
            transition: all 0.3s ease;
            white-space: nowrap;
        }

        .nav-links a:hover {
            background-color: #333333;
            color: #00ff88;
        }

        .hero-section {
            background: linear-gradient(135deg, #000000, #1a1a1a);
            padding: 120px 20px;
            text-align: center;
            position: relative;
            overflow: hidden;
        }

        .hero-content {
            max-width: 1200px;
            margin: 0 auto;
        }

        .hero-content h1 {
            font-size: 0.5rem;
            margin-bottom: 1.5rem;
            background: linear-gradient(45deg, #00ff88, #ffffff);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        footer {
            background-color: #1a1a1a;
            color: white;
            text-align: center;
            padding: 2rem;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            min-height: 100px; /* Adjust height as needed */
        }
        
        footer p {
            margin: 0.5rem 0;
            line-height: 1.5;
        }
        
        footer p:first-child {
            color: #00ff88; /* Company name color */
        }
        
        footer p:last-child {
            color: #888888; /* Partner info color */
        }

        .social-links {
            margin-top: 1rem;
        }

        .social-links a {
            color: white;
            margin: 0 0.5rem;
            font-size: 1.2rem;
        }

</style>
    
</head>

<body>
  <script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-5161795548023023"
  crossorigin="anonymous"></script>


    <div class="top-bar">
      <div>
        <a href="Enterprise Solutions.html">Enterprise Solutions</a>
        <a href="support.html">Support</a>
        <a href="kontakt.html">Kontakt</a>
    </div>
        <div>
            <a href="#">+46 764375307</a>
            <a href="Bibelstudion.html">info@Bibelstudionab.se</a>
        </div>
    </div>
    <header class="header">
      <div class="logo">
          <a href="index.html" style="text-decoration: none; color: inherit;">
              <span>Bibel</span>Studion
          </a>
      </div>
      
      <div class="search-bar">
        <input type="text" placeholder="Sök efter tjänster eller produkter...">
        <button>Sök</button>
    </div>
        <div class="user-actions">
            <a href="login.html" class="action-link" id="loginToggle">
                <i class="fas fa-user"></i>
                <span>Logga in</span>
            </a>

            <a href="kundvagn.html" class="action-link">
                <i class="fas fa-shopping-cart"></i>
                <span>Kundvagn</span>
            </a>
        </div>

        
        <style>
        .user-actions {
            display: flex;
            gap: 25px;
            align-items: center;
        }
        
        .action-link {
            color: #00ff88;
            text-decoration: none;
            display: flex;
            align-items: center;
            gap: 8px;
            transition: all 0.3s ease;
            padding: 10px 15px;
            border-radius: 5px;
        }
        
        .action-link:hover {
            background-color: rgba(0, 255, 136, 0.1);
            transform: translateY(-2px);
        }
        
        .action-link i {
            font-size: 1.2em;
        }
        
        /* Responsiv design */
        @media (max-width: 768px) {
            .user-actions {
                gap: 15px;
            }
            
            .action-link span {
                display: none;
            }
            
            .action-link i {
                font-size: 1.5em;
            }
        }
        </style>
        
        <!-- Lägg till Font Awesome i headern -->
        <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">


<!-- Login Modal -->
<div class="login-modal" id="loginModal">
    <div class="modal-content">
        <button class="close-modal">&times;</button>
        
        <div class="auth-container">
            <div class="auth-header">
                <i class="fas fa-user-shield main-icon"></i>
                <h2>Välkommen tillbaka</h2>
            </div>

            <form id="loginForm" class="auth-form">
                <div class="input-group">
                    <input type="email" id="email" placeholder="E-postadress" required>
                    <i class="fas fa-envelope input-icon"></i>
                </div>

                <div class="input-group">
                    <input type="password" id="password" placeholder="Lösenord" required>
                    <i class="fas fa-lock input-icon"></i>
                    <button type="button" class="password-toggle">
                        <i class="fas fa-eye"></i>
                    </button>
                </div>

                <button type="submit" class="auth-btn">
                    <span class="btn-text">Logga in</span>
                    <div class="loading-dots"></div>
                </button>

                <div class="auth-footer">
                  <p>Ny hos oss? <a href="#" class="register-link">Skapa konto</a></p>
                </div>
            </form>
        </div>
    </div>
</div>

<style>
/* Modal Design */
.login-modal {
    display: none;
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: rgba(26, 26, 26, 0.95);
    z-index: 1000;
    justify-content: center;
    align-items: center;
    backdrop-filter: blur(5px);
}

.modal-content {
    background: #1a1a1a;
    padding: 2rem;
    border-radius: 12px;
    border: 1px solid #00ff88;
    width: 90%;
    max-width: 400px;
    position: relative;
    transform: scale(0.95);
    transition: transform 0.3s ease;
}

.login-modal.active {
    display: flex;
    animation: modalFadeIn 0.3s forwards;
}

@keyframes modalFadeIn {
    from { opacity: 0; }
    to { opacity: 1; }
}

/* Input Fields */
.input-group {
    position: relative;
    margin: 1.5rem 0;
}

input {
    width: 90%;
    padding: 12px 40px 12px 15px;
    background: #2a2a2a;
    border: 1px solid #333;
    border-radius: 8px;
    color: white;
    transition: all 0.3s ease;
}

input:focus {
    border-color: #00ff88;
    box-shadow: 0 0 0 3px rgba(0, 255, 136, 0.1);
}

.input-icon {
    position: absolute;
    right: 15px;
    top: 50%;
    transform: translateY(-50%);
    color: #666;
}

.auth-btn {
    width: 100%;
    padding: 15px;
    background: #00ff88;
    color: #1a1a1a;
    border: none;
    border-radius: 8px;
    font-weight: bold;
    cursor: pointer;
    margin-top: 1rem;
    transition: all 0.3s ease;
}

.auth-btn:hover {
    transform: translateY(-2px);
    box-shadow: 0 5px 15px rgba(0, 255, 136, 0.3);
}

.close-modal {
    position: absolute;
    top: 15px;
    right: 15px;
    color: #00ff88;
    font-size: 1.5rem;
    background: none;
    border: none;
    cursor: pointer;
}
</style>

<script>
// Modal Toggle
const loginModal = document.getElementById('loginModal');
const loginToggle = document.getElementById('loginToggle');

loginToggle.addEventListener('click', (e) => {
    e.preventDefault();
    loginModal.classList.toggle('active');
    document.body.style.overflow = loginModal.classList.contains('active') ? 'hidden' : 'auto';
});

// Close Modal
document.addEventListener('click', (e) => {
    if (e.target === loginModal || e.target.closest('.close-modal')) {
        loginModal.classList.remove('active');
        document.body.style.overflow = 'auto';
    }
});

// Password Toggle
document.querySelectorAll('.password-toggle').forEach(button => {
    button.addEventListener('click', () => {
        const input = button.previousElementSibling;
        input.type = input.type === 'password' ? 'text' : 'password';
        button.querySelector('i').classList.toggle('fa-eye-slash');
    });
});

// Form Handling
document.getElementById('loginForm').addEventListener('submit', async (e) => {
    e.preventDefault();
    const btn = e.target.querySelector('button[type="submit"]');
    
    btn.disabled = true;
    btn.classList.add('loading');

    // Simulerat API-anrop
    setTimeout(() => {
        btn.disabled = false;
        btn.classList.remove('loading');
        loginModal.classList.remove('active');
        // Uppdatera användargränssnittet här efter lyckad inloggning
        document.querySelector('.user-actions').innerHTML = `
            <div class="user-profile">
                <i class="fas fa-user-check"></i>
                <span>Mitt Konto</span>
            </div>
        `;
    }, 1500);
});

// ESC Key to Close
document.addEventListener('keydown', (e) => {
    if (e.key === 'Escape' && loginModal.classList.contains('active')) {
        loginModal.classList.remove('active');
        document.body.style.overflow = 'auto';
    }
});
</script>


<!-- Knapp för att öppna Skapa Konto-modalen -->
<button id="registerToggle" style="margin: 4px; padding: 10px 20px; background: #00ff88; color: #1a1a1a; border: none; border-radius: 5px; cursor: pointer;">
  Registrera
</button>


<!-- Skapa Konto Modal -->
<div class="register-modal" id="registerModal">
  <div class="modal-content">
      <button class="close-modal">&times;</button>
      
      <div class="auth-container">
          <div class="auth-header">
              <i class="fas fa-user-plus main-icon"></i>
              <h2>Skapa ett konto</h2>
              <p>Bli en del av vår community</p>
          </div>

          <form id="registerForm" class="auth-form">
              <div class="input-group">
                  <input type="text" id="fullName" placeholder="Fullständigt namn" required>
                  <i class="fas fa-user input-icon"></i>
              </div>

              <div class="input-group">
                  <input type="email" id="registerEmail" placeholder="E-postadress" required>
                  <i class="fas fa-envelope input-icon"></i>
              </div>

              <div class="input-group">
                  <input type="password" id="registerPassword" placeholder="Lösenord" required>
                  <i class="fas fa-lock input-icon"></i>
                  <button type="button" class="password-toggle">
                      <i class="fas fa-eye"></i>
                  </button>
              </div>

              <div class="input-group">
                  <input type="password" id="confirmPassword" placeholder="Bekräfta lösenord" required>
                  <i class="fas fa-lock input-icon"></i>
                  <button type="button" class="password-toggle">
                      <i class="fas fa-eye"></i>
                  </button>
              </div>

              <button type="submit" class="auth-btn">
                  <span class="btn-text">Skapa konto</span>
                  <div class="loading-dots"></div>
              </button>
          </form>
      </div>
  </div>
</div>

<!-- Font Awesome för ikoner -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">

<style>
/* Modal Design */
.register-modal {
  display: none;
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: rgba(26, 26, 26, 0.95);
  z-index: 1000;
  justify-content: center;
  align-items: center;
  backdrop-filter: blur(5px);
}

.register-modal.active {
  display: flex;
  animation: modalFadeIn 0.3s forwards;
}

@keyframes modalFadeIn {
  from { opacity: 0; }
  to { opacity: 1; }
}

.modal-content {
  background: #1a1a1a;
  padding: 2rem;
  border-radius: 12px;
  border: 1px solid #00ff88;
  width: 90%;
  max-width: 400px;
  position: relative;
  transform: scale(0.95);
  transition: transform 0.3s ease;
}

/* Header */
.auth-header {
  text-align: center;
  margin-bottom: 1.5rem;
}

.auth-header .main-icon {
  font-size: 2.5rem;
  color: #00ff88;
  margin-bottom: 0.5rem;
}

.auth-header h2 {
  color: #00ff88;
  font-size: 1.8em;
  margin: 0.5rem 0;
}

.auth-header p {
  color: #ccc;
  font-size: 0.9em;
}

/* Input Fields */
.input-group {
  position: relative;
  margin: 1.5rem 0;
}

input {
  width: 90%;
  padding: 12px 40px 12px 15px;
  background: #2a2a2a;
  border: 1px solid #333;
  border-radius: 8px;
  color: white;
  transition: all 0.3s ease;
}

input:focus {
  border-color: #00ff88;
  box-shadow: 0 0 0 3px rgba(0, 255, 136, 0.1);
}

.input-icon {
  position: absolute;
  right: 15px;
  top: 50%;
  transform: translateY(-50%);
  color: #666;
}

.password-toggle {
  position: absolute;
  right: 40px;
  top: 50%;
  transform: translateY(-50%);
  background: none;
  border: none;
  color: #666;
  cursor: pointer;
}

/* Submit Button */
.auth-btn {
  width: 100%;
  padding: 15px;
  background: #00ff88;
  color: #1a1a1a;
  border: none;
  border-radius: 8px;
  font-weight: bold;
  cursor: pointer;
  margin-top: 1rem;
  transition: all 0.3s ease;
}

.auth-btn:hover {
  transform: translateY(-2px);
  box-shadow: 0 5px 15px rgba(0, 255, 136, 0.3);
}

/* Close Button */
.close-modal {
  position: absolute;
  top: 15px;
  right: 15px;
  color: #00ff88;
  font-size: 1.5rem;
  background: none;
  border: none;
  cursor: pointer;
}

/* Loading Animation */
.loading-dots {
  display: none;
  justify-content: center;
  gap: 4px;
  margin-left: 8px;
}

.loading-dots::after {
  content: '';
  width: 6px;
  height: 6px;
  background: #1a1a1a;
  border-radius: 50%;
  animation: bounce 1s infinite;
}

.loading-dots::before {
  content: '';
  width: 6px;
  height: 6px;
  background: #1a1a1a;
  border-radius: 50%;
  animation: bounce 1s infinite 0.2s;
}

.loading-dots span {
  width: 6px;
  height: 6px;
  background: #1a1a1a;
  border-radius: 50%;
  animation: bounce 1s infinite 0.4s;
}

@keyframes bounce {
  0%, 100% { transform: translateY(0); }
  50% { transform: translateY(-4px); }
}

.auth-btn.loading .btn-text {
  display: none;
}

.auth-btn.loading .loading-dots {
  display: flex;
}

</style>

<script>
// Modal Toggle
const registerModal = document.getElementById('registerModal');
const registerToggle = document.getElementById('registerToggle');

registerToggle.addEventListener('click', (e) => {
  e.preventDefault();
  registerModal.classList.add('active');
  document.body.style.overflow = 'hidden';
});

// Close Modal
document.addEventListener('click', (e) => {
  if (e.target === registerModal || e.target.closest('.close-modal')) {
      registerModal.classList.remove('active');
      document.body.style.overflow = 'auto';
  }
});

// Password Toggle
document.querySelectorAll('.password-toggle').forEach(button => {
  button.addEventListener('click', () => {
      const input = button.previousElementSibling;
      input.type = input.type === 'password' ? 'text' : 'password';
      button.querySelector('i').classList.toggle('fa-eye-slash');
  });
});

// Form Handling
document.getElementById('registerForm').addEventListener('submit', async (e) => {
  e.preventDefault();
  const btn = e.target.querySelector('button[type="submit"]');
  
  btn.disabled = true;
  btn.classList.add('loading');

  // Simulerat API-anrop för registrering
  setTimeout(() => {
      btn.disabled = false;
      btn.classList.remove('loading');
      registerModal.classList.remove('active');
      alert('Registrering lyckades! Välkommen.');
  }, 1500);
});

// ESC Key to Close
document.addEventListener('keydown', (e) => {
  if (e.key === 'Escape' && registerModal.classList.contains('active')) {
      registerModal.classList.remove('active');
      document.body.style.overflow = 'auto';
  }
});
</script>



    </header>

    <nav class="nav-links">
        <a href="index.html">Hem</a>
        <a href="om oss.html">Om oss</a>
        <a href="karriär.html">Karriär</a>
        <a href="nyhetsbrev.html">Nyhetsbrev</a>
        <a href="Fritid.html">Butik</a>
        <a href="medlemskap.html">Medlemskap</a>
        <a href="skolan.html">Skolan</a>
        <a href="gava.html">Ge en Gåva</a>
        <a href="bible.html">Bibel</a>
        <a href="5 stjärnor.html">5 stjärnor</a>
        <a href="vara-tjanster.html">Tjänster</a>
    </nav>

    <a href="Fritid.html">
      <div style="background: url('image/Skärmbild_15-2-2025_152618_www.temu.com.jpeg') no-repeat center center/cover; color: white; width: 100%; height: 100vh; font-family: Arial, sans-serif; text-align: center;">
      </div>
  </a>
  
    
     
    <section
      style="background-color: #0a0a0a; color: white; padding: 4rem 1rem; font-family: 'Arial', sans-serif;">
        <style>
          .nyheter-container {
            max-width: 1400px;
            margin: 0 auto;
          }
      
          .nyheter-rubrik {
            text-align: center;
            font-size: 2.5em;
            margin-bottom: 3rem;
            color: #00ff88;
            text-transform: uppercase;
            letter-spacing: 2px;
            position: relative;
          }
      
          .nyheter-rubrik::after {
            content: '';
            display: block;
            width: 60px;
            height: 3px;
            background: #00ff88;
            margin: 1rem auto;
          }
      
          .nyheter-grid {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 2rem;
          }
      
          .nyhetskort {
            background: rgba(255, 255, 255, 0.05);
            border-radius: 10px;
            overflow: hidden;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
          }
      
          .nyhetskort:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 32px rgba(0, 255, 136, 0.2);
          }
      
          .nyhetsbild {
            width: 100%;
            height: 200px;
            object-fit: cover;
            border-bottom: 3px solid #00ff88;
          }
      
          .nyhetsinnehåll {
            padding: 1.5rem;
          }
      
          .nyhetskategori {
            color: #00ff88;
            font-size: 0.9em;
            font-weight: bold;
            text-transform: uppercase;
            margin-bottom: 0.5rem;
          }
      
          .nyhetsdatum {
            color: #888;
            font-size: 0.9em;
            margin-bottom: 0.5rem;
          }
      
          .nyhetstitel {
            font-size: 1.4em;
            margin-bottom: 1rem;
            line-height: 1.4;
          }
      
          .nyhetstitel a {
            color: white;
            text-decoration: none;
          }
      
          .nyhetstitel a:hover {
            color: #00ff88;
          }
      
          .nyhetsbeskrivning {
            font-size: 1em;
            color: #ccc;
            line-height: 1.6;
            margin-bottom: 1.5rem;
          }
      
          .läs-mer {
            color: #00ff88;
            text-decoration: none;
            font-weight: bold;
            display: inline-block;
            margin-top: 1rem;
            transition: color 0.3s ease;
          }
      
          .läs-mer:hover {
            color: white;
          }
      
          @media (max-width: 768px) {
            .nyheter-grid {
              grid-template-columns: 1fr;
            }
      
            .nyheter-rubrik {
              font-size: 2em;
            }
          }
        </style>
      
        <div class="nyheter-container">
          <h2 class="nyheter-rubrik">Senaste Nyheterna</h2>
          
          <div class="nyheter-grid">
            <!-- Nyhetskort 1 -->
            <article class="nyhetskort">
              <img src="image/image.png" alt="Bibelstudiebild" class="nyhetsbild">
              <div class="nyhetsinnehåll">
                <div class="nyhetskategori">Bibelstudier</div>
                <div class="nyhetsdatum">15 Maj 2025</div>
                <h3 class="nyhetstitel"><a href="#">Nytt Studiepaket: Jesus Bergspredikan</a></h3>
                <p class="nyhetsbeskrivning">Upptäck djupare insikter från Matteus 5-7 med vårt nya studieunderlag...</p>
                <a href="#" class="läs-mer">Läs mer →</a>
              </div>
            </article>
      
            <!-- Nyhetskort 2 -->
            <article class="nyhetskort">
              <img src="image/learning-dutch-online-young-woman-in-park-with-laptop-768x512.jpg" alt="Gruppstudie" class="nyhetsbild">
              <div class="nyhetsinnehåll">
                <div class="nyhetskategori">Evenemang</div>
                <div class="nyhetsdatum">12 Maj 2024</div>
                <h3 class="nyhetstitel"><a href="#">Sommarens Studiecirklar</a></h3>
                <p class="nyhetsbeskrivning">Anmäl dig nu till våra kommande gemenskapliga bibelstudier...</p>
                <a href="#" class="läs-mer">Läs mer →</a>
              </div>
            </article>
      
            <!-- Nyhetskort 3 -->
            <article class="nyhetskort">
              <img src="image/Podcast-Segment-Ideas-2.jpg" alt="Podcast" class="nyhetsbild">
              <div class="nyhetsinnehåll">
                <div class="nyhetskategori">Podcast</div>
                <div class="nyhetsdatum">10 Maj 2024</div>
                <h3 class="nyhetstitel"><a href="#">Ny Podcast: Profeternas Roll</a></h3>
                <p class="nyhetsbeskrivning">Lyssna på vår nya serie om Gamla testamentets profeter...</p>
                <a href="#" class="läs-mer">Läs mer →</a>
              </div>
            </article>
      
            <!-- Nyhetskort 4 -->
            <article class="nyhetskort">
              <img src="image/R.jpg" alt="Lovsång" class="nyhetsbild">
              <div class="nyhetsinnehåll">
                <div class="nyhetskategori">Musik</div>
                <div class="nyhetsdatum">8 Maj 2024</div>
                <h3 class="nyhetstitel"><a href="#">Nya Lovsånger för 2024</a></h3>
                <p class="nyhetsbeskrivning">Upptäck de senaste lovsångerna som tar din tro till nya höjder...</p>
                <a href="#" class="läs-mer">Läs mer →</a>
              </div>
            </article>
      
            <!-- Nyhetskort 5 -->
            <article class="nyhetskort">
              <img src="image/internal_uncover-modern-identity-and-access-management-iam-challenges-with-enterprise-design-thinking.webp" alt="Workshop" class="nyhetsbild">
              <div class="nyhetsinnehåll">
                <div class="nyhetskategori">Workshop</div>
                <div class="nyhetsdatum">5 Maj 2024</div>
                <h3 class="nyhetstitel"><a href="#">Workshop: Bibelns Symbolik</a></h3>
                <p class="nyhetsbeskrivning">Lär dig tolka symboler och metaforer i Bibeln på vår workshop...</p>
                <a href="#" class="läs-mer">Läs mer →</a>
              </div>
            </article>
      
            <!-- Nyhetskort 6 -->
            <article class="nyhetskort">
              <img src="image/SOSB0324009_1560x880_desktop.jpg" alt="Blogg" class="nyhetsbild">
              <div class="nyhetsinnehåll">
                <div class="nyhetskategori">Blogg</div>
                <div class="nyhetsdatum">1 Maj 2024</div>
                <h3 class="nyhetstitel"><a href="#">5 Sätt att Fördjupa Din Tro</a></h3>
                <p class="nyhetsbeskrivning">Läs våra bästa tips för att stärka din relation med Gud...</p>
                <a href="#" class="läs-mer">Läs mer →</a>
              </div>
            </article>
          </div>
        </div>
      </section>
   




<section class="affiliate-program" style="background-color: #0a0a0a; color: white; padding: 4rem 1rem;">
    <div class="affiliate-container" style="max-width: 1200px; margin: 0 auto;">
        <!-- Rubriksektion -->
        <div class="section-header" style="text-align: center; margin-bottom: 3rem;">
            <h2 style="font-size: 2.5rem; color: #00ff88; margin-bottom: 1rem;">Bli en Bibelstudio Partner</h2>
            <p style="font-size: 1.1rem; color: #cccccc; max-width: 800px; margin: 0 auto;">
                Gör skillnad och tjäna samtidigt du sprider kunskap om Bibeln genom vårt affiliate-program
            </p>
        </div>

        <!-- Grid-container -->
        <div class="program-grid" style="display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 2rem; padding: 1rem;">
            <!-- Vänsterkolumn - Förmåner -->
            <div class="benefits-column" style="background: #111111; padding: 2rem; border-radius: 8px;">
                <h3 style="color: #00ff88; font-size: 1.5rem; margin-bottom: 1.5rem;">Dina Förmåner</h3>
                <ul style="list-style: none; padding: 0;">
                    <li style="margin-bottom: 1.5rem; display: flex; align-items: start; gap: 1rem;">
                        <span style="color: #00ff88; font-size: 1.2rem;">✓</span>
                        <div>
                            <h4 style="margin: 0 0 0.5rem 0; color: #ffffff;">Generös provision</h4>
                            <p style="color: #cccccc; margin: 0;">Tjäna upp till 30% på varje försäljning</p>
                        </div>
                    </li>
                    <li style="margin-bottom: 1.5rem; display: flex; align-items: start; gap: 1rem;">
                        <span style="color: #00ff88; font-size: 1.2rem;">✓</span>
                        <div>
                            <h4 style="margin: 0 0 0.5rem 0; color: #ffffff;">Exklusiva resurser</h4>
                            <p style="color: #cccccc; margin: 0;">Specialmaterial för affiliates</p>
                        </div>
                    </li>
                    <li style="margin-bottom: 1.5rem; display: flex; align-items: start; gap: 1rem;">
                        <span style="color: #00ff88; font-size: 1.2rem;">✓</span>
                        <div>
                            <h4 style="margin: 0 0 0.5rem 0; color: #ffffff;">Realtidsstatistik</h4>
                            <p style="color: #cccccc; margin: 0;">Följ din prestation direkt</p>
                        </div>
                    </li>
                </ul>
            </div>

            <!-- Högerkolumn - Steg -->
            <div class="steps-column" style="background: #111111; padding: 2rem; border-radius: 8px;">
                <h3 style="color: #00ff88; font-size: 1.5rem; margin-bottom: 1.5rem;">Så funkar det</h3>
                <div class="steps" style="counter-reset: step-counter;">
                    <div style="display: flex; gap: 1rem; margin-bottom: 2rem;">
                        <div style="width: 40px; height: 40px; background: #00ff88; border-radius: 50%; display: flex; align-items: center; justify-content: center; color: #0a0a0a; font-weight: bold;">
                            1
                        </div>
                        <div>
                            <h4 style="margin: 0 0 0.5rem 0; color: #ffffff;">Registrera dig</h4>
                            <p style="color: #cccccc; margin: 0;">Skapa ett gratis affiliate-konto</p>
                        </div>
                    </div>
                    <div style="display: flex; gap: 1rem; margin-bottom: 2rem;">
                        <div style="width: 40px; height: 40px; background: #00ff88; border-radius: 50%; display: flex; align-items: center; justify-content: center; color: #0a0a0a; font-weight: bold;">
                            2
                        </div>
                        <div>
                            <h4 style="margin: 0 0 0.5rem 0; color: #ffffff;">Sprid budskapet</h4>
                            <p style="color: #cccccc; margin: 0;">Använd dina unika affiliate-länkar</p>
                        </div>
                    </div>
                    <div style="display: flex; gap: 1rem;">
                        <div style="width: 40px; height: 40px; background: #00ff88; border-radius: 50%; display: flex; align-items: center; justify-content: center; color: #0a0a0a; font-weight: bold;">
                            3
                        </div>
                        <div>
                            <h4 style="margin: 0 0 0.5rem 0; color: #ffffff;">Få utbetalt</h4>
                            <p style="color: #cccccc; margin: 0;">Månatliga utbetalningar via ditt valda sätt</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <!-- CTA Knapp -->
        <div style="text-align: center; margin-top: 3rem;">
            <a href="vara-tjanster.html" style="display: inline-block; padding: 1rem 2rem; background-color: #00ff88; color: #0a0a0a; text-decoration: none; border-radius: 5px; font-weight: bold; transition: transform 0.3s ease;">
                Bli Affiliate Nu
            </a>
        </div>
    </div>
</section>

<!-- Font Awesome för ikoner (om behövs) -->
<script src="https://kit.fontawesome.com/your-kit-code.js" crossorigin="anonymous"></script>


<section style="background-color: #0a0a0a; color: white; padding: 4rem 1rem; font-family: 'Arial', sans-serif;">
    <style>
      .quiz-container {
        max-width: 800px;
        margin: 0 auto;
        background: rgba(255, 255, 255, 0.05);
        border-radius: 15px;
        padding: 2rem;
        box-shadow: 0 8px 32px rgba(0, 0, 0, 0.3);
      }
  
      .quiz-header {
        text-align: center;
        margin-bottom: 2rem;
        padding-bottom: 1rem;
        border-bottom: 2px solid #00ff88;
      }
  
      .question-counter {
        color: #00ff88;
        font-size: 0.9em;
        letter-spacing: 1px;
      }
  
      .question-text {
        font-size: 1.4em;
        line-height: 1.6;
        margin: 1.5rem 0;
      }
  
      .options-list {
        list-style: none;
        padding: 0;
        display: flex;
        flex-direction: column;
        gap: 1rem;
      }
  
      .option-item {
        background: rgba(255, 255, 255, 0.1);
        padding: 1.2rem;
        border-radius: 8px;
        cursor: pointer;
        transition: all 0.3s ease;
      }
  
      .option-item:hover {
        background: #00ff88;
        color: #0a0a0a;
        transform: translateX(10px);
      }
  
      .option-item.selected {
        background: #00ff88;
        color: #0a0a0a;
      }
  
      .option-item.correct {
        outline: 2px solid #00ff88;
      }
  
      .option-item.wrong {
        outline: 2px solid #ff4650;
      }
  
      .quiz-progress {
        height: 4px;
        background: rgba(255, 255, 255, 0.1);
        margin-top: 2rem;
        border-radius: 2px;
      }
  
      .progress-bar {
        height: 100%;
        width: 0;
        background: #00ff88;
        border-radius: 2px;
        transition: width 0.3s ease;
      }
  
      .next-button {
        background: #00ff88;
        color: #0a0a0a;
        border: none;
        padding: 1rem 2.5rem;
        font-weight: bold;
        border-radius: 25px;
        margin-top: 2rem;
        cursor: pointer;
        float: right;
        transition: transform 0.2s ease;
      }
  
      .next-button:hover {
        transform: scale(1.05);
      }
  
      .next-button:disabled {
        background: #555;
        cursor: not-allowed;
      }
  
      .score-board {
        text-align: center;
        font-size: 1.5em;
        padding: 2rem;
      }
  
      .restart-btn {
        background: #00ff88;
        color: #0a0a0a;
        border: none;
        padding: 1rem 2rem;
        margin: 1rem auto;
        display: block;
        cursor: pointer;
        border-radius: 25px;
      }
      .result-message {
        font-size: 1.5em;
        margin: 1rem 0;
        color: #00ff88;
      }
      
      .recommendation {
        font-size: 1.2em;
        margin: 1rem 0;
        color: #ccc;
      }


    </style>
  
    <div class="quiz-container">
      <div class="quiz-header">
        <div class="question-counter">FRÅGA 1 AV 10</div>
        <h1 style="margin: 1rem 0; text-transform: uppercase; letter-spacing: 2px;">Bibelquiz</h1>
      </div>
  
      <div class="question-content">
        <div class="question-text">
          Vilken av dessa personer var känd som "Kärlekens apostel"?
        </div>
  
        <ul class="options-list">
          <li class="option-item" data-correct="false">Petrus</li>
          <li class="option-item" data-correct="false">Pavel</li>
          <li class="option-item" data-correct="true">Johannes</li>
          <li class="option-item" data-correct="false">Jakob</li>
        </ul>
      </div>
  
      <div class="quiz-progress">
        <div class="progress-bar"></div>
      </div>
  
      <button class="next-button" disabled>Nästa fråga →</button>
    </div>
  
    <script>
      const quizData = [
        {
          question: "Vilken av dessa personer var känd som 'Kärlekens apostel'?",
          options: [
            { text: "Petrus", correct: false },
            { text: "Pavel", correct: false },
            { text: "Johannes", correct: true },
            { text: "Jakob", correct: false }
          ]
        },
        {
          question: "Vem skrev de flesta breven i Nya Testamentet?",
          options: [
            { text: "Petrus", correct: false },
            { text: "Pavel", correct: true },
            { text: "Johannes", correct: false },
            { text: "Jesaja", correct: false }
          ]
        },
        {
          question: "Vilken bok i Bibeln börjar med orden 'I början skapade Gud...'?",
          options: [
            { text: "Psaltaren", correct: false },
            { text: "Johannes", correct: false },
            { text: "1 Mosebok", correct: true },
            { text: "Uppenbarelseboken", correct: false }
          ]
        },
        {
          question: "Vem var den första kungen i Israel?",
          options: [
            { text: "David", correct: false },
            { text: "Salomo", correct: false },
            { text: "Saul", correct: true },
            { text: "Mose", correct: false }
          ]
        },
        {
          question: "Vilken stad förstördes av eld som regnade från himlen?",
          options: [
            { text: "Jeriko", correct: false },
            { text: "Sodom", correct: true },
            { text: "Ninive", correct: false },
            { text: "Babel", correct: false }
          ]
        },
        {
          question: "Vem var den första människan som Gud skapade?",
          options: [
            { text: "Eva", correct: false },
            { text: "Adam", correct: true },
            { text: "Noa", correct: false },
            { text: "Abraham", correct: false }
          ]
        },
        {
          question: "Vilket djur talade till Bileam?",
          options: [
            { text: "En orm", correct: false },
            { text: "En åsna", correct: true },
            { text: "En lejon", correct: false },
            { text: "En örn", correct: false }
          ]
        },
        {
          question: "Vem blev kastad i lejongropen men överlevde?",
          options: [
            { text: "Daniel", correct: true },
            { text: "David", correct: false },
            { text: "Jona", correct: false },
            { text: "Josef", correct: false }
          ]
        },
        {
          question: "Vem var Jesus mor?",
          options: [
            { text: "Maria", correct: true },
            { text: "Marta", correct: false },
            { text: "Rebekka", correct: false },
            { text: "Ester", correct: false }
          ]
        },
        {
          question: "Vilken apostel förnekade Jesus tre gånger?",
          options: [
            { text: "Judas", correct: false },
            { text: "Petrus", correct: true },
            { text: "Tomas", correct: false },
            { text: "Andreas", correct: false }
          ]
        }
      ];
  
      let currentQuestion = 0;
      let score = 0;
      const questionContent = document.querySelector('.question-content');
      const progressBar = document.querySelector('.progress-bar');
      const nextBtn = document.querySelector('.next-button');
      const questionCounter = document.querySelector('.question-counter');
  
      function loadQuestion(index) {
        const q = quizData[index];
        questionContent.innerHTML = `
          <div class="question-text">${q.question}</div>
          <ul class="options-list">
            ${q.options.map(opt => `
              <li class="option-item" data-correct="${opt.correct}">
                ${opt.text}
              </li>
            `).join('')}
          </ul>
        `;
  
        document.querySelectorAll('.option-item').forEach(option => {
          option.addEventListener('click', handleOptionClick);
        });
      }
  
      function handleOptionClick() {
        const isCorrect = this.dataset.correct === 'true';
        document.querySelectorAll('.option-item').forEach(opt => {
          opt.classList.remove('selected', 'correct', 'wrong');
          if (opt.dataset.correct === 'true') opt.classList.add('correct');
        });
  
        this.classList.add('selected');
        if (!isCorrect) this.classList.add('wrong');
  
        if (isCorrect) score++;
  
        document.querySelectorAll('.option-item').forEach(opt => {
          opt.style.pointerEvents = 'none';
        });
  
        nextBtn.disabled = false;
      }
  
      function updateProgress() {
        const progress = ((currentQuestion + 1) / quizData.length) * 100;
        progressBar.style.width = `${progress}%`;
        questionCounter.textContent = `FRÅGA ${currentQuestion + 1} AV ${quizData.length}`;
      }
  
      function showResults() {
        let message = "";
        let recommendation = "";
      
        if (score === 10) {
          message = "Fantastiskt! Du är en bibel-expert! 🎉";
          recommendation = "Dela dina kunskaper med andra och fortsätt att fördjupa dig i Bibeln.";
        } else if (score >= 7) {
          message = "Bra jobbat! Du har goda bibelkunskaper. 🌟";
          recommendation = "Fortsätt läsa Bibeln regelbundet för att bli ännu bättre.";
        } else if (score >= 4) {
          message = "Du har en god grund! 👍";
          recommendation = "Öva på att läsa Bibeln varje dag och testa quizet igen senare.";
        } else {
          message = "Ingen fara, alla börjar någonstans! 😊";
          recommendation = "Börja med att läsa de mest kända berättelserna, som Skapelsen eller Jesu liv.";
        }
      
        document.querySelector('.quiz-container').innerHTML = `
          <div class="score-board">
            <h2>Quiz avslutat!</h2>
            <p>Din poäng: ${score} av ${quizData.length}</p>
            <p class="result-message">${message}</p>
            <p class="recommendation">${recommendation}</p>
            <button class="restart-btn" onclick="location.reload()">Gör om quizet</button>
          </div>
          <a href="https://www.bibeln.se" target="_blank">Läs Bibeln online</a> |
    <a href="https://www.bibelstudier.se" target="_blank">Bibelstudier för nybörjare</a>
  </p>
</div>
        `;
      }
  
      nextBtn.addEventListener('click', () => {
        currentQuestion++;
        if (currentQuestion < quizData.length) {
          loadQuestion(currentQuestion);
          updateProgress();
          nextBtn.disabled = true;
        } else {
          showResults();
        }
      });
  
      // Initiera quiz
      loadQuestion(currentQuestion);
      updateProgress();
    </script>
  </section>








  <section style="background-color: #0a0a0a; color: white; padding: 4rem 1rem; font-family: 'Arial', sans-serif;">
    <style>
      .video-gallery {
        max-width: 1200px;
        margin: 0 auto;
        padding: 2rem;
      }
  
      .video-gallery h2 {
        text-align: center;
        font-size: 2.5em;
        margin-bottom: 2rem;
        color: #00ff88;
        text-transform: uppercase;
        letter-spacing: 2px;
      }
  
      .video-grid {
        display: grid;
        grid-template-columns: repeat(4, 1fr);
        gap: 1.5rem;
      }
  
      .video-card {
        background: rgba(255, 255, 255, 0.05);
        border-radius: 10px;
        overflow: hidden;
        transition: transform 0.3s ease, box-shadow 0.3s ease;
      }
  
      .video-card:hover {
        transform: translateY(-10px);
        box-shadow: 0 8px 32px rgba(0, 255, 136, 0.2);
      }
  
      .video-card iframe {
        width: 100%;
        height: 200px;
        border: none;
        border-radius: 10px 10px 0 0;
      }
  
      .video-card h3 {
        font-size: 1.2em;
        padding: 1rem;
        margin: 0;
        color: #00ff88;
        text-align: center;
      }
  
      @media (max-width: 768px) {
        .video-grid {
          grid-template-columns: repeat(2, 1fr);
        }
      }
  
      @media (max-width: 480px) {
        .video-grid {
          grid-template-columns: 1fr;
        }
      }
    </style>
  
    <div class="video-gallery">
      <h2>Populära kristna videor</h2>
      <div class="video-grid">
        <!-- Video 1 -->
        <div class="video-card">
          <iframe src="https://www.youtube.com/embed/RYmpAgu55zc" allowfullscreen></iframe>
          <h3>Därför firar vi påsk!</h3>
        </div>
        <!-- Video 2 -->
        <div class="video-card">
          <iframe src="https://www.youtube.com/embed/FSckJpjiNZk" allowfullscreen></iframe>
          <h3>Översikt: Jesaja 1-39</h3>
        </div>
        <!-- Video 3 -->
        <div class="video-card">
          <iframe src="https://www.youtube.com/embed/P0NTawveaZw" allowfullscreen></iframe>
          <h3>Jesus är Kärlek</h3>
        </div>
        <!-- Video 4 -->
        <div class="video-card">
          <iframe src="https://www.youtube.com/embed/xpPvC1ke9m4" allowfullscreen></iframe>
          <h3>Vad kan Jesus göra?</h3>
        </div>
        <!-- Video 5 -->
        <div class="video-card">
          <iframe src="https://www.youtube.com/embed/oWk9dmMadpE" allowfullscreen></iframe>
          <h3>Jesus sover inte | </h3>
        </div>
        <!-- Video 6 -->
        <div class="video-card">
          <iframe src="https://www.youtube.com/embed/SoXLe8Iytz0" allowfullscreen></iframe>
          <h3>Jesus utmanar |</h3>
        </div>
        <!-- Video 7 -->
        <div class="video-card">
          <iframe src="https://www.youtube.com/embed/M7DLoM_NUzQ" allowfullscreen></iframe>
          <h3>Guds ord till helande |</h3>
        </div>
        <!-- Video 8 -->
        <div class="video-card">
          <iframe src="https://www.youtube.com/embed/NO9zNMBZ_y4" allowfullscreen></iframe>
          <h3>Karolinas vittnesbörd |</h3>
        </div>
      </div>
    </div>
  </section>






  <section style="background-color: #0a0a0a; color: white; padding: 4rem 1rem; font-family: 'Arial', sans-serif;">
    <style>
      .tiktok-gallery {
        max-width: 1200px;
        margin: 0 auto;
        padding: 2rem;
      }
      .tiktok-gallery h2 {
        text-align: center;
        font-size: 2.5em;
        margin-bottom: 2rem;
        color: #00ff88;
        text-transform: uppercase;
        letter-spacing: 2px;
      }
      .tiktok-grid {
        display: grid;
        grid-template-columns: repeat(4, 1fr);
        gap: 1.5rem;
      }
      .tiktok-card {
        background: rgba(255, 255, 255, 0.05);
        border-radius: 10px;
        overflow: hidden;
        transition: transform 0.3s ease, box-shadow 0.3s ease;
      }
      .tiktok-card:hover {
        transform: translateY(-10px);
        box-shadow: 0 8px 32px rgba(0, 255, 136, 0.2);
      }
      .tiktok-card blockquote {
        margin: 0;
      }
      .tiktok-card h3 {
        font-size: 1.2em;
        padding: 1rem;
        margin: 0;
        color: #00ff88;
        text-align: center;
      }
      @media (max-width: 768px) {
        .tiktok-grid {
          grid-template-columns: repeat(2, 1fr);
        }
      }
      @media (max-width: 480px) {
        .tiktok-grid {
          grid-template-columns: 1fr;
        }
      }
    </style>
    <div class="tiktok-gallery">
      <h2>Populära TikTok Videor</h2>
      <div class="tiktok-grid">
        <!-- TikTok Video 1 -->
        <div class="tiktok-card">
          <blockquote class="tiktok-embed" cite="https://www.tiktok.com/@bibelstudion/video/7455075726140640534" data-video-id="7455075726140640534" style="max-width: 605px;min-width: 325px;">
            <section> <a target="_blank" title="@bibelstudion" href="https://www.tiktok.com/@bibelstudion">@bibelstudion</a> 
              <p>Inspirerande budskap från Bibeln</p> 
              <a target="_blank" title="♬ original sound - Bibelstudion" href="https://www.tiktok.com/music/original-sound-7455075761231260462">♬ original sound - Bibelstudion</a> 
            </section>
          </blockquote> 
          <script async src="https://www.tiktok.com/embed.js"></script>
          <h3>Bibelns Kraft</h3>
        </div>
        <!-- TikTok Video 2 -->
        <div class="tiktok-card">
          <blockquote class="tiktok-embed" cite="https://www.tiktok.com/@bibelstudion/video/7440535698559618326" data-video-id="7440535698559618326" style="max-width: 605px;min-width: 325px;">
            <section> <a target="_blank" title="@bibelstudion" href="https://www.tiktok.com/@bibelstudion">@bibelstudion</a> 
              <p>Lär dig mer om Bibelns visdom</p> 
              <a target="_blank" title="♬ original sound - Bibelstudion" href="https://www.tiktok.com/music/original-sound-7440535731232762666">♬ original sound - Bibelstudion</a> 
            </section>
          </blockquote> 
          <script async src="https://www.tiktok.com/embed.js"></script>
          <h3>Bibelns Visdom</h3>
        </div>
        <!-- TikTok Video 3 -->
        <div class="tiktok-card">
          <blockquote class="tiktok-embed" cite="https://www.tiktok.com/@gudssanning/video/7294631347962793249" data-video-id="7294631347962793249" style="max-width: 605px;min-width: 325px;">
            <section> <a target="_blank" title="@gudssanning" href="https://www.tiktok.com/@gudssanning">@gudssanning</a> 
              <p>Jesus Kristus - Frälsaren</p> 
              <a target="_blank" title="♬ original sound - Gudssanning" href="https://www.tiktok.com/music/original-sound-7294631381230209824">♬ original sound - Gudssanning</a> 
            </section>
          </blockquote> 
          <script async src="https://www.tiktok.com/embed.js"></script>
          <h3>Jesus Kristus</h3>
        </div>
        <!-- TikTok Video 4 -->
        <div class="tiktok-card">
          <blockquote class="tiktok-embed" cite="https://www.tiktok.com/@esteban.aaliyah/video/7290954382617742624" data-video-id="7290954382617742624" style="max-width: 605px;min-width: 325px;">
            <section> <a target="_blank" title="@esteban.aaliyah" href="https://www.tiktok.com/@esteban.aaliyah">@esteban.aaliyah</a> 
              <p>Tro och förtröstan</p> 
              <a target="_blank" title="♬ original sound - Esteban & Aaliyah" href="https://www.tiktok.com/music/original-sound-7290954415218338561">♬ original sound - Esteban & Aaliyah</a> 
            </section>
          </blockquote> 
          <script async src="https://www.tiktok.com/embed.js"></script>
          <h3>Tro och Förtröstan</h3>
        </div>
        <!-- TikTok Video 5 -->
        <div class="tiktok-card">
          <blockquote class="tiktok-embed" cite="https://www.tiktok.com/@petrus.eurell/video/7220025727318625541" data-video-id="7220025727318625541" style="max-width: 605px;min-width: 325px;">
            <section> <a target="_blank" title="@petrus.eurell" href="https://www.tiktok.com/@petrus.eurell">@petrus.eurell</a> 
              <p>Bibelns budskap</p> 
              <a target="_blank" title="♬ original sound - Petrus Eurell" href="https://www.tiktok.com/music/original-sound-7220025761230760965">♬ original sound - Petrus Eurell</a> 
            </section>
          </blockquote> 
          <script async src="https://www.tiktok.com/embed.js"></script>
          <h3>Bibelns Budskap</h3>
        </div>
        <!-- TikTok Video 6 -->
        <div class="tiktok-card">
          <blockquote class="tiktok-embed" cite="https://www.tiktok.com/@praesten_johnny/video/7428231674988743969" data-video-id="7428231674988743969" style="max-width: 605px;min-width: 325px;">
            <section> <a target="_blank" title="@praesten_johnny" href="https://www.tiktok.com/@praesten_johnny">@praesten_johnny</a> 
              <p>Prästen Johnny delar visdom</p> 
              <a target="_blank" title="♬ original sound - Prästen Johnny" href="https://www.tiktok.com/music/original-sound-7428231711233837857">♬ original sound - Prästen Johnny</a> 
            </section>
          </blockquote> 
          <script async src="https://www.tiktok.com/embed.js"></script>
          <h3>Prästen Johnny</h3>
        </div>
        <!-- TikTok Video 7 -->
        <div class="tiktok-card">
          <blockquote class="tiktok-embed" cite="https://www.tiktok.com/@svtnyheter/video/7450862675225005345" data-video-id="7450862675225005345" style="max-width: 605px;min-width: 325px;">
            <section> <a target="_blank" title="@svtnyheter" href="https://www.tiktok.com/@svtnyheter">@svtnyheter</a> 
              <p>Nyheter om tro och samhälle</p> 
              <a target="_blank" title="♬ original sound - SVT Nyheter" href="https://www.tiktok.com/music/original-sound-7450862711233837857">♬ original sound - SVT Nyheter</a> 
            </section>
          </blockquote> 
          <script async src="https://www.tiktok.com/embed.js"></script>
          <h3>Tro och Samhälle</h3>
        </div>
        <!-- TikTok Video 8 -->
        <div class="tiktok-card">
          <blockquote class="tiktok-embed" cite="https://www.tiktok.com/@vandra.med.gud/video/7437618177992985879" data-video-id="7437618177992985879" style="max-width: 605px;min-width: 325px;">
            <section> <a target="_blank" title="@vandra.med.gud" href="https://www.tiktok.com/@vandra.med.gud">@vandra.med.gud</a> 
              <p>Vandra med Gud</p> 
              <a target="_blank" title="♬ original sound - Vandra med Gud" href="https://www.tiktok.com/music/original-sound-7437618211233837857">♬ original sound - Vandra med Gud</a> 
            </section>
          </blockquote> 
          <script async src="https://www.tiktok.com/embed.js"></script>
          <h3>Vandra med Gud</h3>
        </div>
      </div>
    </div>
  </section>


  <a href="https://temu.to/m/uazz1ry8z6t" style="text-decoration:none; color:inherit;">
    <section style="background:#ff7729; color:white; padding:20px; text-align:center; border-radius:10px;">
        <h2 style="color:#00ff88; font-size:28px; margin-bottom:15px;">Bibelstudion Affiliate Program</h2>
        <p style="font-size:18px; margin-bottom:20px;">Gå med i vårt affiliate-program och tjäna provision genom att dela vår länk!</p>
        <div style="display:inline-block; background:#00ff88; color:#0a0a0a; padding:12px 20px; font-size:16px; font-weight:bold; text-decoration:none; border-radius:5px; transition:0.3s;">
            Gå med nu
        </div>
    </section>
</a>

<script src="https://apis.google.com/js/platform.js"></script>

<div class="g-ytsubscribe" data-channel="GoogleDevelopers" data-layout="full" data-theme="dark" data-count="default"></div>

<section id="faq" class="faq-section" style="background-color: #0a0a0a; color: white; padding: 4rem 1rem;">
    <div class="faq-container" style="max-width: 800px; margin: 0 auto;">
        <!-- Rubrik och beskrivning -->
        <h2 style="font-size: 2.5rem; text-align: center; margin-bottom: 1rem; color: #00ff88;">Vanliga Frågor (FAQ)</h2>
        <p style="text-align: center; font-size: 1.1rem; color: #cccccc; margin-bottom: 3rem;">
            Här hittar du svar på några av de vanligaste frågorna vi får. Klicka på en fråga för att visa svaret.
        </p>

        <!-- FAQ-objekt -->
        <div class="faq-item" style="border-bottom: 1px solid #333; padding: 1.5rem 0;">
            <div class="faq-question" style="font-size: 1.2rem; font-weight: bold; color: #00ff88; cursor: pointer;">
                Vad erbjuder er bibelstudio?
                <span style="float: right;">+</span>
            </div>
            <div class="faq-answer" style="display: none; padding-top: 1rem; color: #cccccc;">
                Vi erbjuder gruppstudier, personlig rådgivning, onlinekurser och mycket mer för att hjälpa dig fördjupa din förståelse för Bibeln.
            </div>
        </div>

        <div class="faq-item" style="border-bottom: 1px solid #333; padding: 1.5rem 0;">
            <div class="faq-question" style="font-size: 1.2rem; font-weight: bold; color: #00ff88; cursor: pointer;">
                Är era tjänster kostnadsfria?
                <span style="float: right;">+</span>
            </div>
            <div class="faq-answer" style="display: none; padding-top: 1rem; color: #cccccc;">
                Ja, alla våra tjänster är helt kostnadsfria. Vi vill göra Bibeln tillgänglig för alla.
            </div>
        </div>

        <div class="faq-item" style="border-bottom: 1px solid #333; padding: 1.5rem 0;">
            <div class="faq-question" style="font-size: 1.2rem; font-weight: bold; color: #00ff88; cursor: pointer;">
                Behöver jag ha tidigare kunskap om Bibeln?
                <span style="float: right;">+</span>
            </div>
            <div class="faq-answer" style="display: none; padding-top: 1rem; color: #cccccc;">
                Nej, våra studier är anpassade för både nybörjare och de som redan har en djupare förståelse.
            </div>
        </div>

        <div class="faq-item" style="border-bottom: 1px solid #333; padding: 1.5rem 0;">
            <div class="faq-question" style="font-size: 1.2rem; font-weight: bold; color: #00ff88; cursor: pointer;">
                Kan jag delta online?
                <span style="float: right;">+</span>
            </div>
            <div class="faq-answer" style="display: none; padding-top: 1rem; color: #cccccc;">
                Ja, vi erbjuder både fysiska och digitala möjligheter att delta i våra studier.
            </div>
        </div>

        <div class="faq-item" style="border-bottom: 1px solid #333; padding: 1.5rem 0;">
            <div class="faq-question" style="font-size: 1.2rem; font-weight: bold; color: #00ff88; cursor: pointer;">
                Hur anmäler jag mig till en studie?
                <span style="float: right;">+</span>
            </div>
            <div class="faq-answer" style="display: none; padding-top: 1rem; color: #cccccc;">
                Du kan anmäla dig direkt på vår hemsida eller kontakta oss via e-post eller telefon.
            </div>
        </div>
    </div>
</section>












<script>
    // JavaScript för att visa/dölja svar
    document.querySelectorAll('.faq-question').forEach(item => {
        item.addEventListener('click', () => {
            const answer = item.nextElementSibling;
            const icon = item.querySelector('span');
            if (answer.style.display === 'none' || answer.style.display === '') {
                answer.style.display = 'block';
                icon.textContent = '−';
            } else {
                answer.style.display = 'none';
                icon.textContent = '+';
            }
        });
    });
</script>

    <footer>
        <div class="info-container">
            <div class="info-item">
                <h2>Följ Bibelstudion</h2>
                <p>Följ oss på sociala medier för senaste nyheter och erbjudanden.</p>
                <ul>
                    <li><a href="https://www.facebook.com/Bibelstudion.23">Facebook</a></li>
                    <li><a href="https://www.tiktok.com/@bibelstudion1">TikTok</a></li>
                    <li><a href="https://www.youtube.com/channel/UCbr9n2H-FZ0ZltRjcLqASng">YouTube</a></li>
                    <a class="AppLink_AppLink__uXETs" href="https://apps.apple.com/us/app/mathem/id1076840480?ign-itscg=30200&amp;ign-itsct=apps_box_badge"><img class="k-image" width="139" height="50" loading="lazy" decoding="async" alt="App store badge" src="https://cdn.sanity.io/images/1teetjp9/production/d06e2189e4d6f74d74fb05c26c47efb1a1117967-120x40.svg"></a>
                    <a class="AppLink_AppLink__uXETs" href="https://play.google.com/store/apps/details?id=se.mathem.mathem&amp;pcampaignid=web_share"><img class="k-image" width="139" height="50" loading="lazy" decoding="async" alt="Google play badge" src="https://cdn.sanity.io/images/1teetjp9/production/b46ac873f892190c97f30eed0e1042a585f6c813-646x250.png"></a>
                </ul>
            </div>
    
            <div class="info-item">
                <h2>Ladda ner</h2>
                <p>Få tillgång till exklusiva erbjudanden och spåra dina beställningar via vår app.</p>
                <ul>
                    <li><a href="Prisvarningar.html">Prisvarningar</a></li>
                    <li><a href="Varningar om låga lagervaror.html">Varningar om låga lagervaror</a></li>
                    <li><a href="Kuponger & Erbjudanden.html">Kuponger & Erbjudanden</a></li>
                </ul>
            </div>
    
            <div class="info-item">
                <h2>Kundtjänst</h2>
                <p>Vänligen kontakta oss om du har några frågor om våra tjänster.</p>
                <ul>
                    <li><a href="Retur- och återbetalningspolicy.html">Retur- och återbetalningspolicy</a></li>
                    <li><a href="Fraktinformation.html">Fraktinformation</a></li>
                    <li><a href="support.html">Hjälp & Support</a></li>
                    <li><a href="Bibelstudion köpskydd.html">Bibelstudion Köpskydd</a></li>
                </ul>
            </div>
    
            <div class="info-item">
                <h2>Om Företaget</h2>
                <p>Här kan du läsa om Bibelstudion, våra värderingar och hur vi arbetar.</p>
                <ul>
                    <li><a href="om oss.html">Om Bibelstudion</a></li>
                    <li><a href="affiliate.html">Affiliate & Influencer: Tjäna Provision</a></li>
                    <li><a href="karriär.html">Karriär</a></li>
                </ul>
            </div>
        </div>
    </footer>
    
    <style>
    footer {
        background-color: #1a1a1a;
        color: white;
        padding: 40px 20px;
        font-family: Arial, sans-serif;
    }
    
    .info-container {
        max-width: 1200px;
        margin: 0 auto;
        display: flex;
        flex-wrap: wrap;
        justify-content: space-between;
        gap: 30px;
    }
    
    .info-item {
        flex: 1;
        min-width: 250px;
        margin: 15px 0;
    }
    
    .info-item h2 {
        color: #00ff88;
        font-size: 1.2em;
        margin-bottom: 15px;
    }
    
    .info-item p {
        font-size: 0.9em;
        line-height: 1.6;
        margin-bottom: 15px;
        opacity: 0.9;
    }
    
    .info-item ul {
        list-style: none;
        padding: 0;
    }
    
    .info-item li {
        margin-bottom: 8px;
    }
    
    .info-item a {
        color: white;
        text-decoration: none;
        font-size: 0.9em;
        transition: color 0.3s ease;
    }
    
    .info-item a:hover {
        color: #00ff88;
        text-decoration: underline;
    }
    
    @media (max-width: 768px) {
        .info-container {
            flex-direction: column;
        }
        
        .info-item {
            text-align: center;
        }
        
        .info-item ul {
            display: flex;
            flex-direction: column;
            align-items: center;
        }
    }
    </style>

    <!-- Resten av innehållet förblir oförändrat -->
    <section class="footer" style="background-color: #0a0a0a; color: white; padding: 40px 20px; font-family: 'Arial', sans-serif; border-top: 2px solid #00ff88;">
        <div class="footer-content" style="max-width: 1200px; margin: 0 auto; display: flex; justify-content: space-between; align-items: center; flex-wrap: wrap;">
            <div class="footer-info">
                <h3 style="color: #00ff88; margin-bottom: 15px; font-size: 1.2em;">Bibelstudion AB</h3>
                <p style="margin: 5px 0; font-size: 0.9em;">© 2024 Bibelstudion AB. Alla rättigheter reserverade.</p>
                <p style="color: #00ff88; margin: 5px 0; font-size: 0.9em; font-weight: 300;">
                    Certifierad partner: <span style="color: #ffffff;">Microsoft Gold Partner | AWS Advanced Tier</span>
                </p>
            </div>
            
            <div class="social-links" style="margin-top: 15px;">
                <a href="https://www.facebook.com/Bibelstudion.23" style="color: white; margin: 0 10px; font-size: 1.5em; transition: color 0.3s ease; text-decoration: none;">
                    <i class="fab fa-facebook"></i>
                </a>
                <a href="https://www.tiktok.com/@bibelstudion1" style="color: white; margin: 0 10px; font-size: 1.5em; transition: color 0.3s ease; text-decoration: none;">
                    <i class="fab fa-tiktok"></i>
                </a>
                <a href="https://www.linkedin.com/" style="color: white; margin: 0 10px; font-size: 1.5em; transition: color 0.3s ease; text-decoration: none;">
                    <i class="fab fa-linkedin"></i>
                </a>
            </div>
        </div>
    </section>

    <section id="cookie-consent" style="background-color: #0a0a0a; color: white; padding: 10px; font-family: Arial, sans-serif; position: fixed; bottom: 0; left: 0; right: 0; z-index: 1000; box-shadow: 0 -2px 5px rgba(0, 0, 0, 0.5); width: 100%; text-align: center;">
      <h2 style="color: #00ff88; font-size: 18px; margin-bottom: 5px;">Vi använder webbkakor</h2>
      <p style="font-size: 12px; line-height: 1.5;">Vi använder webbkakor för din bästa möjliga upplevelse. Läs mer om vår <a href="Våra Regler.html" style="color: #00ff88; text-decoration: underline;">hantering av personuppgifter</a>.</p>
      <div style="margin-top: 10px; display: flex; justify-content: center; gap: 5px;">
        <button id="accept-cookies" style="background-color: #00ff88; color: #0a0a0a; padding: 5px 10px; border: none; border-radius: 5px; cursor: pointer; font-weight: bold; font-size: 12px;">Acceptera</button>
        <button id="decline-cookies" style="background-color: transparent; color: #00ff88; padding: 5px 10px; border: 1px solid #00ff88; border-radius: 5px; cursor: pointer; font-weight: bold; font-size: 12px;">Avvisa</button>
      </div>
    </section>
    
    <script>
      document.getElementById('accept-cookies').addEventListener('click', function() {
        document.getElementById('cookie-consent').style.display = 'none';
        localStorage.setItem('cookiesAccepted', 'true');
      });
    
      document.getElementById('decline-cookies').addEventListener('click', function() {
        document.getElementById('cookie-consent').style.display = 'none';
        localStorage.setItem('cookiesAccepted', 'false');
      });
    
      window.addEventListener('load', function() {
        if (localStorage.getItem('cookiesAccepted')) {
          document.getElementById('cookie-consent').style.display = 'none';
        }
      });
    </script>
    
    <style>
        .footer a:hover {
            color: #00ff88 !important;
        }
        
        @media (max-width: 768px) {
            .footer-content {
                flex-direction: column;
                text-align: center;
            }
            
            .social-links {
                margin-top: 20px !important;
            }
        }


    </style>

  
</body>
</html>
<!--Start of Tawk.to Script-->
<script type="text/javascript">
  var Tawk_API=Tawk_API||{}, Tawk_LoadStart=new Date();
  (function(){
  var s1=document.createElement("script"),s0=document.getElementsByTagName("script")[0];
  s1.async=true;
  s1.src='https://embed.tawk.to/67b0bca7fb6773190d790aa1/1ik561s69';
  s1.charset='UTF-8';
  s1.setAttribute('crossorigin','*');
  s0.parentNode.insertBefore(s1,s0);
  })();
  </script>
  <!--End of Tawk.to Script-->
















