<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Sistema Escolar</title>
<style>
*{box-sizing:border-box;margin:0;padding:0}
body{font-family:Arial,Helvetica,sans-serif;background:#f3f6fa;color:#263238;display:flex;min-height:100vh}
.sidebar{width:245px;background:#123b67;color:white;min-height:100vh;padding:22px 14px}
.logo{font-size:22px;font-weight:bold;padding:10px 14px 25px}
.menu-btn{width:100%;border:0;background:transparent;color:white;text-align:left;padding:14px;border-radius:8px;font-size:16px;cursor:pointer;margin-bottom:5px}
.menu-btn:hover,.menu-btn.active{background:#1e568d}
.arrow{float:right;transition:.2s}
.menu-btn.active .arrow{transform:rotate(90deg)}
.submenu{display:none;padding-left:10px}
.submenu.show{display:block}
.sub-btn{width:100%;border:0;background:#0d3156;color:#eaf3fb;text-align:left;padding:12px;border-radius:7px;font-size:14px;cursor:pointer;margin:3px 0}
.sub-btn:hover{background:#27669d}
.main{flex:1}
.topbar{height:70px;background:white;display:flex;align-items:center;padding:0 30px;box-shadow:0 2px 8px #00000012}
.topbar h1{font-size:22px;color:#123b67}
.content{padding:35px}
.card{background:white;border-radius:14px;padding:28px;box-shadow:0 3px 14px #00000010;max-width:900px}
.card h2{color:#123b67;margin-bottom:10px}
.welcome{font-size:28px;margin-bottom:8px}
.cards{display:flex;gap:18px;flex-wrap:wrap;margin-top:25px}
.room{border:1px solid #dbe4ed;border-radius:12px;padding:22px;width:260px;cursor:pointer;background:#fff;transition:.2s}
.room:hover{transform:translateY(-3px);box-shadow:0 6px 18px #00000012}
.room h3{color:#123b67;margin-bottom:8px}
.room p{color:#657482}
.badge{display:inline-block;background:#e8f1fa;color:#16558a;padding:5px 9px;border-radius:20px;font-size:12px;margin-bottom:12px}
</style>
</head>
<body>
<aside class="sidebar">
  <div class="logo">📚 Sistema Escolar</div>

  <button class="menu-btn" onclick="inicio()">🏠 Inicio</button>

  <button class="menu-btn" id="salonesBtn" onclick="toggleSalones()">
    🏫 Salones <span class="arrow">›</span>
  </button>

  <div class="submenu" id="salonesMenu">
    <button class="sub-btn" onclick="mostrarSalon('Secundaria A','Miss Gaela')">Secundaria A — Miss Gaela</button>
    <button class="sub-btn" onclick="mostrarSalon('Secundaria B','Profe Facundo')">Secundaria B — Profe Facundo</button>
  </div>

  <button class="menu-btn" onclick="mostrarTodosAlumnos()">👨‍🎓 Alumnos</button>
  <button class="menu-btn" onclick="proximamente('Profesores')">👩‍🏫 Profesores</button>
  <button class="menu-btn" onclick="proximamente('Horarios')">📅 Horarios</button>
</aside>

<main class="main">
  <header class="topbar"><h1 id="titulo">Inicio</h1></header>
  <section class="content" id="contenido">
    <div class="card">
      <div class="welcome">Bienvenido al sistema escolar 👋</div>
      <p>Usa el menú de la izquierda para entrar a <b>Salones</b>.</p>
    </div>
  </section>
</main>

<script>
function toggleSalones(){
  const menu=document.getElementById('salonesMenu');
  const btn=document.getElementById('salonesBtn');
  menu.classList.toggle('show');
  btn.classList.toggle('active');
}
function inicio(){
  document.getElementById('titulo').textContent='Inicio';
  document.getElementById('contenido').innerHTML=`
    <div class="card">
      <div class="welcome">Bienvenido al sistema escolar 👋</div>
      <p>Usa el menú de la izquierda para entrar a <b>Salones</b>.</p>
    </div>`;
}
function mostrarTodosAlumnos(){
  document.getElementById('titulo').textContent='Alumnos';
  document.getElementById('contenido').innerHTML=`
    <div class="card">
      <span class="badge">REGISTRO DE ALUMNOS</span>
      <h2>Todos los alumnos</h2>
      <p style="margin-top:8px">Puedes colocar una nota para cada alumno.</p>

      <h3 style="margin-top:25px;color:#123b67">🏫 Secundaria A — Miss Gaela</h3>
      <div class="cards">
        ${alumnoConNota('Valentina','Secundaria A')}
        ${alumnoConNota('Ian','Secundaria A')}
        ${alumnoConNota('Sofia','Secundaria A')}
        ${alumnoConNota('Sebas H','Secundaria A')}
      </div>

      <h3 style="margin-top:30px;color:#123b67">🏫 Secundaria B — Profe Facundo</h3>
      <div class="cards">
        ${alumnoConNota('Ethan','Secundaria B')}
        ${alumnoConNota('Thiago','Secundaria B')}
        ${alumnoConNota('Flavia','Secundaria B')}
      </div>
    </div>`;
}

function alumnoConNota(nombre,salon){
  const id='notas_'+salon.replace(/\s/g,'_')+'_'+nombre.replace(/\s/g,'_');
  return `
    <div class="room" style="width:100%">
      <h3>👤 ${nombre}</h3>
      <p>${salon}</p>
      <div id="${id}_lista" style="margin-top:14px">
        ${crearNota(id,nombre,1)}
      </div>
      <button onclick="agregarNota('${id}','${nombre}')"
        style="margin-top:10px;padding:9px 13px;border:0;border-radius:7px;background:#27669d;color:white;cursor:pointer">
        + Agregar otra nota
      </button>
      <button onclick="mostrarHistorial('${id}','${nombre}','${salon}')"
        style="margin-top:10px;padding:9px 13px;border:0;border-radius:7px;background:#4b6f8f;color:white;cursor:pointer">
        📋 Historial de notas
      </button>
      <button onclick="guardarTodas('${id}','${nombre}')"
        style="margin-top:10px;padding:9px 13px;border:0;border-radius:7px;background:#123b67;color:white;cursor:pointer">
        Guardar notas
      </button>
      <span id="${id}_msg" style="display:block;margin-top:8px;font-size:13px"></span>
    </div>`;
}

function crearNota(id,nombre,numero){
  return `
    <div class="nota-fila" style="display:flex;gap:8px;align-items:center;margin-top:8px;flex-wrap:wrap">
      <span class="dia-label" style="min-width:70px;font-weight:bold">Día 1:</span>
      <input type="date" class="fecha-nota"
        style="padding:9px;border:1px solid #ccd7e2;border-radius:7px">
      <select class="valor-nota"
        style="padding:9px;border:1px solid #ccd7e2;border-radius:7px;font-size:15px">
        <option value="">Nota</option>
        <option value="Z">Z</option>
        <option value="C">C</option>
        <option value="B-">B-</option>
        <option value="B">B</option>
        <option value="B+">B+</option>
        <option value="A">A</option>
        <option value="A+">A+</option>
        <option value="AD">AD</option>
      </select>
    </div>`;
}

function actualizarDias(id){
  const lista=document.getElementById(id+'_lista');
  const filas=[...lista.querySelectorAll('.nota-fila')];
  const fechas=[...new Set(filas.map(f=>f.querySelector('.fecha-nota').value).filter(Boolean))].sort();
  filas.forEach(fila=>{
    const fecha=fila.querySelector('.fecha-nota').value;
    const label=fila.querySelector('.dia-label');
    if(!fecha){ label.textContent='Día —:'; return; }
    const dia=fechas.indexOf(fecha)+1;
    label.textContent='Día '+dia+':';
  });
}

function agregarNota(id,nombre){
  const lista=document.getElementById(id+'_lista');
  const numero=lista.querySelectorAll('.nota-fila').length+1;
  lista.insertAdjacentHTML('beforeend',crearNota(id,nombre,numero));
  actualizarDias(id);
  lista.querySelectorAll('.fecha-nota').forEach(input=>input.onchange=()=>actualizarDias(id));
}

function guardarTodas(id,nombre){
  const lista=document.getElementById(id+'_lista');
  const filas=lista.querySelectorAll('.nota-fila');
  const registros=[];
  let valido=true;

  filas.forEach((fila)=>{
    const fecha=fila.querySelector('.fecha-nota').value;
    const nota=fila.querySelector('.valor-nota').value;
    if(fecha && nota){
      registros.push({fecha,nota});
    } else if(fecha || nota){
      valido=false;
    }
  });

  const mensaje=document.getElementById(id+'_msg');
  if(!valido){
    mensaje.textContent='Completa la fecha y la nota de cada registro.';
    return;
  }

  localStorage.setItem(id,JSON.stringify(registros));
  mensaje.textContent='✓ Notas guardadas: '+registros.length;
  actualizarDias(id);
}

function mostrarHistorial(id,nombre,salon){
  const datos=JSON.parse(localStorage.getItem(id)||'[]');
  document.getElementById('titulo').textContent='Historial de notas';
  let html='<div class="card"><span class="badge">HISTORIAL</span><h2>📋 Historial de '+nombre+'</h2><p style="margin-top:8px">'+salon+'</p>';
  if(!datos.length){
    html+='<div style="margin-top:20px;padding:15px;background:#f3f6fa;border-radius:10px">No hay notas guardadas todavía.</div>';
  }else{
    const porFecha={};
    datos.forEach(r=>(porFecha[r.fecha]??=[]).push(r));
    const fechas=Object.keys(porFecha).sort();
    fechas.forEach((fecha,i)=>{
      html+='<div style="margin-top:20px;border:1px solid #dbe4ed;border-radius:10px;padding:15px"><h3 style="color:#123b67">Día '+(i+1)+' — '+fecha+'</h3>';
      porFecha[fecha].forEach((r,j)=>{html+='<p style="margin-top:8px">Nota '+(j+1)+': <b>'+r.nota+'</b></p>';});
      html+='</div>';
    });
  }
  html+='<button onclick="mostrarTodosAlumnos()" style="margin-top:20px;padding:10px 15px;border:0;border-radius:7px;background:#123b67;color:white;cursor:pointer">← Volver a alumnos</button></div>';
  document.getElementById('contenido').innerHTML=html;
}


function mostrarSalon(salon,profesor){
  document.getElementById('titulo').textContent='Salones';
  document.getElementById('contenido').innerHTML=`
    <div class="card">
      <span class="badge">SALÓN</span>
      <h2>${salon}</h2>
      <p style="margin-top:8px">Responsable: <b>${profesor}</b></p>
      <div class="cards">
        <div class="room" onclick="mostrarAlumnos('${salon}','${profesor}')" style="cursor:pointer">
          <h3>👨‍🎓 Alumnos</h3>
          <p>Ver alumnos de este salón.</p>
        </div>
        <div class="room" style="width:100%">
          <h3>📅 Horario</h3>
          <div class="cards" style="margin-top:12px">
            <div class="room"><h3>📅 Lunes</h3><p>Matemática</p><p>Inglés</p><p>CyT</p></div>
            <div class="room"><h3>📅 Martes</h3><p>Inglés</p><p>Tutoría</p><p>Personal</p></div>
            <div class="room"><h3>📅 Miércoles</h3><p>Inglés</p><p>Personal</p><p>Comu</p></div>
            <div class="room"><h3>📅 Jueves</h3><p>Inglés</p><p>Robótica</p><p>Educ. Física</p></div>
            <div class="room"><h3>📅 Viernes</h3><p>Tutoría</p><p>Arte</p><p>Hora libre</p></div>
          </div>
        </div>
      </div>
    </div>`;
}
function mostrarAlumnos(salon, profesor){
  document.getElementById('titulo').textContent='Alumnos';
  const estudiantes = salon === 'Secundaria A'
    ? ['Valentina','Ian','Sofia','Sebas H']
    : ['Ethan','Thiago','Flavia'];
  const nombreProfesor = salon === 'Secundaria A' ? 'Miss Gaela' : 'Profe Facundo';
  const cards = estudiantes.map(nombre => `
    <div class="room" onclick="mostrarNotasAlumno('${nombre}','${salon}','${nombreProfesor}')" style="cursor:pointer">
      <h3>👤 ${nombre}</h3>
      <p>${salon}</p>
      <p style="margin-top:8px;color:#27669d;font-weight:bold">📝 Ver notas</p>
    </div>`).join('');
  document.getElementById('contenido').innerHTML=`
    <div class="card">
      <span class="badge">${salon.toUpperCase()}</span>
      <h2>Alumnos — ${nombreProfesor}</h2>
      <p style="margin-top:8px">Presiona un alumno para entrar directamente a sus notas.</p>
      <div class="cards">${cards}</div>
      <button onclick="mostrarSalon('${salon}','${nombreProfesor}')" style="margin-top:20px;padding:10px 15px;border:0;border-radius:7px;background:#123b67;color:white;cursor:pointer">← Volver al salón</button>
    </div>`;
}

function mostrarNotasAlumno(nombre,salon,profesor){
  document.getElementById('titulo').textContent='Notas de '+nombre;
  const id='notas_'+salon.replace(/\s/g,'_')+'_'+nombre.replace(/\s/g,'_');
  document.getElementById('contenido').innerHTML=`
    <div class="card">
      <span class="badge">NOTAS DEL ALUMNO</span>
      <h2>📝 ${nombre}</h2>
      <p style="margin-top:8px">${salon} — ${profesor}</p>
      <div style="margin-top:20px">${alumnoConNota(nombre,salon)}</div>
      <button onclick="mostrarAlumnos('${salon}','${profesor}')" style="margin-top:20px;padding:10px 15px;border:0;border-radius:7px;background:#123b67;color:white;cursor:pointer">← Volver a alumnos</button>
    </div>`;
}

function proximamente(nombre){
  document.getElementById('titulo').textContent=nombre;

  if(nombre === 'Profesores'){
    document.getElementById('contenido').innerHTML=`
      <div class="card">
        <span class="badge">PROFESORES</span>
        <h2>Profesores y sus alumnos</h2>
        <div class="cards">
          <div class="room" style="width:100%">
            <h3>👨‍🏫 Profe Facundo</h3>
            <p style="margin-bottom:15px">Secundaria B</p>
            <p>👤 Ethan</p>
            <p>👤 Thiago</p>
            <p>👤 Flavia</p>
          </div>
          <div class="room" style="width:100%">
            <h3>👩‍🏫 Miss Gaela</h3>
            <p style="margin-bottom:15px">Secundaria A</p>
            <p>👤 Valentina</p>
            <p>👤 Ian</p>
            <p>👤 Sofia</p>
            <p>👤 Sebas H</p>
          </div>
        </div>
      </div>`;
    return;
  }

  if(nombre === 'Horarios'){
    document.getElementById('contenido').innerHTML=`
      <div class="card">
        <span class="badge">HORARIO SEMANAL</span>
        <h2>Horario de clases</h2>
        <div class="cards">
          <div class="room"><h3>📅 Lunes</h3><p>Matemática</p><p>Inglés</p><p>CyT</p></div>
          <div class="room"><h3>📅 Martes</h3><p>Inglés</p><p>Tutoría</p><p>Personal</p></div>
          <div class="room"><h3>📅 Miércoles</h3><p>Inglés</p><p>Personal</p><p>Comu</p></div>
          <div class="room"><h3>📅 Jueves</h3><p>Inglés</p><p>Robótica</p><p>Educ. Física</p></div>
          <div class="room"><h3>📅 Viernes</h3><p>Tutoría</p><p>Arte</p><p>Hora libre</p></div>
        </div>
      </div>`;
    return;
  }

  document.getElementById('contenido').innerHTML=`
    <div class="card">
      <h2>${nombre}</h2>
      <p style="margin-top:10px">Esta sección estará disponible próximamente.</p>
    </div>`;
}
</script>
</body>
</html>
