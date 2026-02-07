/* TIPOGRAFÍA Y ESTILO GENERAL */
body {
  font-family: "Georgia", serif;
  color: #333;
  line-height: 1.7;
  margin: 0;
  padding: 0;
  background-color: #fafafa;
}

h1, h2, h3, h4 {
  font-family: "Georgia", serif;
  color: #2c2c2c;
  margin-bottom: 10px;
}

section {
  padding: 60px 20px;
  max-width: 900px;
  margin: auto;
}

/* HERO */
.hero {
  background: #f2efe9;
  text-align: center;
  padding: 100px 20px;
  border-bottom: 1px solid #ddd;
}

.hero h1 {
  font-size: 2.4rem;
  margin-bottom: 15px;
}

.hero p {
  font-size: 1.2rem;
  margin-bottom: 30px;
  color: #555;
}

.hero-buttons {
  display: flex;
  justify-content: center;
  gap: 15px;
  flex-wrap: wrap;
}

/* BOTONES */
.btn-primary,
.btn-secondary {
  padding: 12px 22px;
  border-radius: 6px;
  text-decoration: none;
  font-weight: bold;
  display: inline-block;
}

.btn-primary {
  background-color: #7a5c3e;
  color: white;
}

.btn-primary:hover {
  background-color: #6a5036;
}

.btn-secondary {
  background-color: #e8e2d9;
  color: #4a3b2a;
  border: 1px solid #c8b8a6;
}

.btn-secondary:hover {
  background-color: #dcd3c8;
}

/* LISTAS */
ul {
  padding-left: 20px;
  margin-top: 10px;
}

li {
  margin-bottom: 8px;
}

/* SERVICIOS */
.servicio {
  background: #ffffff;
  padding: 20px;
  margin: 20px 0;
  border-left: 4px solid #7a5c3e;
  border-radius: 4px;
  box-shadow: 0 1px 3px rgba(0,0,0,0.05);
}

/* EQUIPO */
.miembro-equipo {
  background: #fff;
  padding: 20px;
  border-radius: 6px;
  margin-top: 20px;
  border: 1px solid #e0d8cf;
}

/* OPINIONES */
.opinion {
  background: #fff;
  padding: 20px;
  border-radius: 6px;
  margin: 20px 0;
  border-left: 4px solid #c4b6a6;
  box-shadow: 0 1px 3px rgba(0,0,0,0.05);
}

/* CONTACTO */
.contact-buttons {
  margin-top: 20px;
  display: flex;
  gap: 15px;
  flex-wrap: wrap;
}

/* CTA FIJO EN MÓVIL */
@media (max-width: 768px) {
  .cta-movil {
    position: fixed;
    bottom: 0;
    left: 0;
    width: 100%;
    background: #7a5c3e;
    color: white;
    display: flex;
    justify-content: space-around;
    padding: 12px 0;
    font-size: 1rem;
    z-index: 999;
  }

  .cta-movil a {
    color: white;
    text-decoration: none;
    font-weight: bold;
  }
}