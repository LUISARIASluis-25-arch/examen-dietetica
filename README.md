# examen-dietetica
examen calificado del ppt 
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Quiz: Introducción a la Dietética y Nutrición</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
            background-color: #f4f4f4;
        }
        .container {
            background: white;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        h1 {
            color: #2c5aa0;
            text-align: center;
        }
        .question {
            margin-bottom: 20px;
            padding: 15px;
            border-left: 4px solid #2c5aa0;
            background: #f9f9f9;
        }
        label {
            display: block;
            margin: 10px 0;
            cursor: pointer;
        }
        input[type="radio"] {
            margin-right: 10px;
        }
        button {
            background: #2c5aa0;
            color: white;
            padding: 15px 30px;
            border: none;
            border-radius: 5px;
            font-size: 18px;
            cursor: pointer;
            width: 100%;
        }
        button:hover {
            background: #1e3f70;
        }
        #result {
            display: none;
            text-align: center;
            margin-top: 20px;
            padding: 20px;
            border-radius: 10px;
        }
        .score-perfect { background: #d4edda; color: #155724; }
        .score-good { background: #fff3cd; color: #856404; }
        .score-low { background: #f8d7da; color: #721c24; }
        #unique-id {
            background: #e9ecef;
            padding: 10px;
            border-radius: 5px;
            margin-bottom: 20px;
            text-align: center;
            font-weight: bold;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>🧬 Quiz: Introducción a la Dietética y Nutrición</h1>
        <p><strong>Instrucciones:</strong> Responde las 10 preguntas. Cada una vale <strong>2 puntos</strong> (Total: 20 puntos). Al final obtendrás tu calificación individual. ¡Comparte este enlace único para que otros participen por separado!</p>
        
        <div id="unique-id">
            Tu ID único de sesión: <span id="session-id"></span>
        </div>
        
        <form id="quiz-form">
            <div class="question">
                <h3>1. ¿Qué estudia principalmente la <strong>Nutrición</strong>?</h3>
                <label><input type="radio" name="q1" value="a"> Procesos biológicos y químicos de los nutrientes (ingestión, digestión, etc.)</label>
                <label><input type="radio" name="q1" value="b"> Planificación de regímenes alimentarios</label>
                <label><input type="radio" name="q1" value="c"> Solo el metabolismo de grasas</label>
                <label><input type="radio" name="q1" value="d"> Excreción de vitaminas</label>
            </div>

            <div class="question">
                <h3>2. Los <strong>pilares de la alimentación saludable</strong> son:</h3>
                <label><input type="radio" name="q2" value="a"> Equilibrio, variedad y moderación</label>
                <label><input type="radio" name="q2" value="b"> Carbohidratos, proteínas y grasas</label>
                <label><input type="radio" name="q2" value="c"> Vitaminas A, D, E y K</label>
                <label><input type="radio" name="q2" value="d"> Fibra, agua y minerales</label>
            </div>

            <div class="question">
                <h3>3. ¿Cuál es la <strong>principal fuente de energía</strong> entre los macronutrientes?</h3>
                <label><input type="radio" name="q3" value="a"> Proteínas</label>
                <label><input type="radio" name="q3" value="b"> Carbohidratos</label>
                <label><input type="radio" name="q3" value="c"> Lípidos (grasas)</label>
                <label><input type="radio" name="q3" value="d"> Vitaminas</label>
            </div>

            <div class="question">
                <h3>4. Las <strong>vitaminas liposolubles</strong> son:</h3>
                <label><input type="radio" name="q4" value="a"> C y complejo B</label>
                <label><input type="radio" name="q4" value="b"> A, D, E, K</label>
                <label><input type="radio" name="q4" value="c"> Solo Calcio y Magnesio</label>
                <label><input type="radio" name="q4" value="d"> Hierro y Zinc</label>
            </div>

            <div class="question">
                <h3>5. ¿Qué grupo de alimentos es la <strong>base energética</strong> y aporta fibra y vitaminas B?</h3>
                <label><input type="radio" name="q5" value="a"> Frutas y verduras</label>
                <label><input type="radio" name="q5" value="b"> Cereales y legumbres</label>
                <label><input type="radio" name="q5" value="c"> Lácteos</label>
                <label><input type="radio" name="q5" value="d"> Carnes y pescados</label>
            </div>

            <div class="question">
                <h3>6. La <strong>fibra soluble</strong> ayuda principalmente en el:</h3>
                <label><input type="radio" name="q6" value="a"> Control glucémico (estabiliza azúcar en sangre)</label>
                <label><input type="radio" name="q6" value="b"> Reducción de colesterol LDL</label>
                <label><input type="radio" name="q6" value="c"> Prevención de estreñimiento</label>
                <label><input type="radio" name="q6" value="d"> Formación de huesos</label>
            </div>

            <div class="question">
                <h3>7. En el <strong>Plato de Harvard</strong>, ¿qué debe ocupar la <strong>mitad del plato</strong>?</h3>
                <label><input type="radio" name="q7" value="a"> Granos integrales</label>
                <label><input type="radio" name="q7" value="b"> Proteínas saludables</label>
                <label><input type="radio" name="q7" value="b"> Vegetales y frutas</label>
                <label><input type="radio" name="q7" value="d"> Aceites vegetales</label>
            </div>

            <div class="question">
                <h3>8. Durante el <strong>embarazo y lactancia</strong>, hay incremento en el requerimiento de:</h3>
                <label><input type="radio" name="q8" value="a"> Solo calcio</label>
                <label><input type="radio" name="q8" value="b"> Folato, hierro y energía</label>
                <label><input type="radio" name="q8" value="c"> Grasas saturadas</label>
                <label><input type="radio" name="q8" value="d"> Carbohidratos simples</label>
            </div>

            <div class="question">
                <h3>9. En la <strong>tercera edad</strong>, prioridad nutricional para prevenir sarcopenia y osteoporosis:</h3>
                <label><input type="radio" name="q9" value="a"> Carbohidratos simples</label>
                <label><input type="radio" name="q9" value="b"> Proteínas y Vitamina D</label>
                <label><input type="radio" name="q9" value="c"> Solo fibra insoluble</label>
                <label><input type="radio" name="q9" value="d"> Bebidas azucaradas</label>
            </div>

            <div class="question">
                <h3>10. La <strong>distribución calórica ideal</strong> recomienda mayor porcentaje de:</h3>
                <label><input type="radio" name="q10" value="a"> Grasas saturadas</label>
                <label><input type="radio" name="q10" value="b"> Proteínas animales</label>
                <label><input type="radio" name="q10" value="c"> Carbohidratos complejos</label>
                <label><input type="radio" name="q10" value="d"> Azúcares simples</label>
            </div>

            <button type="button" onclick="calculateScore()">🧮 Calcular Mi Calificación</button>
        </form>

        <div id="result">
            <h2 id="score-text"></h2>
            <p id="score-detail"></p>
            <p><strong>¡Comparte tu puntuación con tu ID único!</strong></p>
        </div>
    </div>

    <script>
        // Generar ID único para cada sesión (para "enlaces únicos" - cada navegador/abrir es único)
        const sessionId = 'quiz_' + Math.random().toString(36).substr(2, 9) + '_' + Date.now();
        document.getElementById('session-id').textContent = sessionId;

        const correctAnswers = {
            q1: 'a',
            q2: 'a',
            q3: 'b',
            q4: 'b',
            q5: 'b',
            q6: 'a',
            q7: 'c',  // Corregido: Vegetales y frutas es c
            q8: 'b',
            q9: 'b',
            q10: 'c'
        };

        function calculateScore() {
            let score = 0;
            const form = document.getElementById('quiz-form');
            const questions = ['q1', 'q2', 'q3', 'q4', 'q5', 'q6', 'q7', 'q8', 'q9', 'q10'];

            questions.forEach(q => {
                const selected = form.querySelector(`input[name="${q}"]:checked`);
                if (selected && selected.value === correctAnswers[q]) {
                    score += 2;
                }
            });

            const percentage = (score / 20) * 100;
            let message = '';
            let className = '';

            if (percentage === 100) {
                message = '¡Excelente! 🎉 Maestro de la Dietética';
                className = 'score-perfect';
            } else if (percentage >= 70) {
                message = '¡Muy bien! 👍 Sólidos conocimientos';
                className = 'score-good';
            } else if (percentage >= 50) {
                message = '¡Bien! 📚 Sigue estudiando';
                className = 'score-low';
            } else {
                message = '¡Ánimo! 🔄 Repásalo y vuélvelo a intentar';
                className = 'score-low';
            }

            document.getElementById('score-text').innerHTML = `<strong>${score}/20 puntos (${percentage.toFixed(0)}%)</strong> - ${message}`;
            document.getElementById('score-detail').textContent = `ID de sesión: ${sessionId} - Calificación individual única.`;
            document.getElementById('result').className = className;
            document.getElementById('result').style.display = 'block';

            // Scroll to result
            document.getElementById('result').scrollIntoView({ behavior: 'smooth' });
        }
    </script>
</body>
</html>
