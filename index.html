<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Escanear IMEI</title>
    <style>
        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
            background-color: #f0f2f5;
            margin: 0;
            padding: 20px;
            display: flex;
            justify-content: center;
            align-items: flex-start;
            min-height: 100vh;
        }
        .container {
            background-color: white;
            padding: 25px;
            border-radius: 12px;
            box-shadow: 0 4px 12px rgba(0,0,0,0.1);
            width: 100%;
            max-width: 500px;
            box-sizing: border-box;
        }
        h1 {
            color: #1c1e21;
            text-align: center;
            margin-bottom: 25px;
        }
        #scanner-container {
            width: 100%;
            border: 1px solid #ddd;
            border-radius: 8px;
            overflow: hidden;
            margin-bottom: 20px;
        }
        .form-group {
            margin-bottom: 15px;
        }
        label {
            display: block;
            margin-bottom: 5px;
            font-weight: 600;
            color: #4b4f56;
        }
        input, select {
            width: 100%;
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 6px;
            box-sizing: border-box;
            font-size: 16px;
        }
        input[readonly] {
            background-color: #e9ebee;
            cursor: not-allowed;
        }
        button {
            width: 100%;
            padding: 12px;
            background-color: #007bff;
            color: white;
            border: none;
            border-radius: 6px;
            font-size: 18px;
            font-weight: bold;
            cursor: pointer;
            transition: background-color 0.3s;
        }
        button:hover {
            background-color: #0056b3;
        }
        .hidden {
            display: none;
        }
        #feedback-message {
            text-align: center;
            padding: 10px;
            margin-top: 15px;
            border-radius: 6px;
            font-weight: bold;
        }
        .success {
            background-color: #d4edda;
            color: #155724;
        }
        .error {
            background-color: #f8d7da;
            color: #721c24;
        }
    </style>
</head>
<body>

    <div class="container">
        <h1>Escanear IMEI</h1>

        <!-- Botón para iniciar el escaneo -->
        <button id="btn-scan">Escanear IMEI con la Cámara</button>

        <!-- Contenedor para el video del escáner -->
        <div id="scanner-container" class="hidden"></div>
        
        <!-- Mensaje de feedback para el usuario -->
        <div id="feedback-message" class="hidden"></div>

        <!-- Formulario que aparece después de escanear -->
        <form id="product-form" class="hidden">
            <div class="form-group">
                <label for="imei">IMEI Escaneado</label>
                <input type="text" id="imei" name="imei" readonly required>
            </div>

            <div class="form-group">
                <label for="modelo">Modelo</label>
                <select id="modelo" name="modelo" required>
                    <option value="" disabled selected>Selecciona un modelo...</option>
                    <optgroup label="iPhone 15 Series">
                        <option value="iPhone 15 Pro Max">iPhone 15 Pro Max</option>
                        <option value="iPhone 15 Pro">iPhone 15 Pro</option>
                        <option value="iPhone 15 Plus">iPhone 15 Plus</option>
                        <option value="iPhone 15">iPhone 15</option>
                    </optgroup>
                    <optgroup label="iPhone 14 Series">
                        <option value="iPhone 14 Pro Max">iPhone 14 Pro Max</option>
                        <option value="iPhone 14 Pro">iPhone 14 Pro</option>
                        <option value="iPhone 14 Plus">iPhone 14 Plus</option>
                        <option value="iPhone 14">iPhone 14</option>
                    </optgroup>
                    <optgroup label="iPhone 13 Series">
                        <option value="iPhone 13 Pro Max">iPhone 13 Pro Max</option>
                        <option value="iPhone 13 Pro">iPhone 13 Pro</option>
                        <option value="iPhone 13 Mini">iPhone 13 Mini</option>
                        <option value="iPhone 13">iPhone 13</option>
                    </optgroup>
                    <optgroup label="iPhone 12 Series">
                        <option value="iPhone 12 Pro Max">iPhone 12 Pro Max</option>
                        <option value="iPhone 12 Pro">iPhone 12 Pro</option>
                        <option value="iPhone 12">iPhone 12</option>
                        <option value="iPhone 12 Mini">iPhone 12 Mini</option>
                    </optgroup>
                     <optgroup label="iPhone 11 Series">
                        <option value="iPhone 11 Pro Max">iPhone 11 Pro Max</option>
                        <option value="iPhone 11 Pro">iPhone 11 Pro</option>
                        <option value="iPhone 11">iPhone 11</option>
                    </optgroup>
                </select>
            </div>

            <div class="form-group">
                <label for="bateria">Condición de Batería (%)</label>
                <input type="number" id="bateria" name="bateria" placeholder="Ej: 89" min="1" max="100" required>
            </div>

            <div class="form-group">
                <label for="color">Color</label>
                <select id="color" name="color" required>
                    <option value="" disabled selected>Selecciona un color...</option>
                    <option value="Negro espacial">Negro espacial</option>
                    <option value="Plata">Plata</option>
                    <option value="Dorado">Dorado</option>
                    <option value="Púrpura oscuro">Púrpura oscuro</option>
                    <option value="Rojo (Product RED)">Rojo (Product RED)</option>
                    <option value="Azul">Azul</option>
                    <option value="Verde">Verde</option>
                    <option value="Blanco estelar">Blanco estelar</option>
                    <option value="Medianoche">Medianoche</option>
                </select>
            </div>

            <div class="form-group">
                <label for="almacenamiento">Almacenamiento</label>
                <select id="almacenamiento" name="almacenamiento" required>
                    <option value="" disabled selected>Selecciona el almacenamiento...</option>
                    <option value="128GB">128 GB</option>
                    <option value="256GB">256 GB</option>
                    <option value="512GB">512 GB</option>
                    <option value="1TB">1 TB</option>
                </select>
            </div>

            <div class="form-group">
                <label for="detalles">Detalles Estéticos</label>
                <select id="detalles" name="detalles" required>
                    <option value="" disabled selected>Selecciona la condición...</option>
                    <option value="Como Nuevo (Sin detalles)">Como Nuevo (Sin detalles)</option>
                    <option value="Excelente (Mínimos detalles)">Excelente (Mínimos detalles)</option>
                    <option value="Bueno (Detalles de uso visibles)">Bueno (Detalles de uso visibles)</option>
                    <option value="Regular (Marcas o rayones notorios)">Regular (Marcas o rayones notorios)</option>
                </select>
            </div>

            <button type="submit">Guardar Producto en Base de Datos</button>
        </form>
    </div>

    <!-- Librería para escanear QR/códigos de barras -->
    <script src="https://unpkg.com/html5-qrcode/html5-qrcode.min.js"></script>

    <!-- Scripts de Firebase -->
    <script src="https://www.gstatic.com/firebasejs/9.6.1/firebase-app-compat.js"></script>
    <script src="https://www.gstatic.com/firebasejs/9.6.1/firebase-firestore-compat.js"></script>

    <script>
        // --- CONFIGURACIÓN DE FIREBASE ---
        // ¡IMPORTANTE! Reemplaza esto con la configuración de tu propio proyecto de Firebase.
        const firebaseConfig = {
            apiKey: "TU_API_KEY",
            authDomain: "TU_AUTH_DOMAIN",
            projectId: "TU_PROJECT_ID",
            storageBucket: "TU_STORAGE_BUCKET",
            messagingSenderId: "TU_MESSAGING_SENDER_ID",
            appId: "TU_APP_ID"
        };

        // Inicializar Firebase
        firebase.initializeApp(firebaseConfig);
        const db = firebase.firestore();

        // --- LÓGICA DE LA APLICACIÓN ---
        const btnScan = document.getElementById('btn-scan');
        const scannerContainer = document.getElementById('scanner-container');
        const productForm = document.getElementById('product-form');
        const imeiInput = document.getElementById('imei');
        const feedbackMessage = document.getElementById('feedback-message');
        
        // Función para mostrar mensajes al usuario
        function showFeedback(message, type) {
            feedbackMessage.textContent = message;
            feedbackMessage.className = `feedback-message ${type}`; // 'success' o 'error'
            feedbackMessage.classList.remove('hidden');
            setTimeout(() => feedbackMessage.classList.add('hidden'), 4000);
        }

        // Crear una instancia del escáner
        const html5QrCode = new Html5Qrcode("scanner-container");

        const onScanSuccess = (decodedText, decodedResult) => {
            // Cuando el escaneo es exitoso
            console.log(`Código escaneado: ${decodedText}`);
            
            // Detener el escáner
            html5QrCode.stop().then(() => {
                scannerContainer.classList.add('hidden');
                
                // Rellenar el campo IMEI y mostrar el formulario
                imeiInput.value = decodedText;
                productForm.classList.remove('hidden');

            }).catch(err => {
                console.error("Error al detener el escáner", err);
            });
        };
        
        const onScanFailure = (error) => {
            // Puedes ignorar los errores comunes de "QR no encontrado"
            // console.warn(`Error de escaneo = ${error}`);
        };

        // Evento para el botón de escanear
        btnScan.addEventListener('click', () => {
            btnScan.classList.add('hidden'); // Ocultar el botón
            scannerContainer.classList.remove('hidden'); // Mostrar el contenedor del escáner

            // Iniciar el escáner
            html5QrCode.start(
                { facingMode: "environment" }, // Usa la cámara trasera del celular
                {
                    fps: 10,    // Frames por segundo
                    qrbox: { width: 250, height: 150 } // Tamaño de la caja de escaneo
                },
                onScanSuccess,
                onScanFailure
            ).catch(err => {
                showFeedback("Error al iniciar la cámara. Asegúrate de dar permisos.", "error");
                console.error("No se pudo iniciar el escáner", err);
                btnScan.classList.remove('hidden');
                scannerContainer.classList.add('hidden');
            });
        });

        // Evento para enviar el formulario
        productForm.addEventListener('submit', async (e) => {
            e.preventDefault(); // Evita que la página se recargue

            const formData = new FormData(productForm);
            const phoneData = {
                imei: formData.get('imei'),
                modelo: formData.get('modelo'),
                bateria: `${formData.get('bateria')}%`, // Añadimos el %
                color: formData.get('color'),
                almacenamiento: formData.get('almacenamiento'),
                detalles: formData.get('detalles'),
                fechaDeCarga: new Date() // Guardamos la fecha y hora del registro
            };

            try {
                // Añadir un nuevo documento a la colección "iphones"
                const docRef = await db.collection("iphones").add(phoneData);
                console.log("Documento escrito con ID: ", docRef.id);
                
                showFeedback(`¡iPhone ${phoneData.modelo} guardado con éxito!`, 'success');

                // Reiniciar la vista
                productForm.reset();
                productForm.classList.add('hidden');
                btnScan.classList.remove('hidden');

            } catch (error) {
                console.error("Error al añadir el documento: ", error);
                showFeedback("Hubo un error al guardar los datos.", "error");
            }
        });
    </script>

</body>
</html>