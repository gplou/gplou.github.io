<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Expense Manager - Privacy Policy / Pol&iacute;tica de Privacidad</title>
    <style>
        body { font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif; max-width: 800px; margin: 0 auto; padding: 20px; line-height: 1.6; color: #333; }
        h1 { color: #1a1a2e; border-bottom: 2px solid #e0e0e0; padding-bottom: 10px; }
        h2 { color: #16213e; margin-top: 30px; }
        .effective-date { color: #666; font-style: italic; }
        .lang-toggle { text-align: right; margin-bottom: 20px; }
        .lang-toggle a { padding: 5px 15px; border: 1px solid #ccc; border-radius: 4px; text-decoration: none; color: #333; margin-left: 5px; }
        .lang-toggle a.active { background: #1a1a2e; color: white; }
        .en { display: none; }
        ul { padding-left: 20px; }
        li { margin-bottom: 8px; }
    </style>
    <script>
        function showLang(lang) {
            document.querySelectorAll('.es, .en').forEach(el => el.style.display = 'none');
            document.querySelectorAll('.' + lang).forEach(el => el.style.display = 'block');
            document.querySelectorAll('.lang-toggle a').forEach(a => a.classList.remove('active'));
            document.querySelector('.lang-toggle a[onclick*="' + lang + '"]').classList.add('active');
        }
    </script>
</head>
<body>
    <div class="lang-toggle">
        <a href="#" onclick="showLang('es'); return false;" class="active">Espa&ntilde;ol</a>
        <a href="#" onclick="showLang('en'); return false;">English</a>
    </div>

    <!-- SPANISH VERSION -->
    <div class="es">
        <h1>Pol&iacute;tica de Privacidad de Expense Manager</h1>
        <p class="effective-date">Fecha de vigencia: 18 de marzo de 2026</p>

        <h2>1. Informaci&oacute;n que Recopilamos</h2>
        <p>Expense Manager recopila la siguiente informaci&oacute;n para proporcionar y mejorar el servicio:</p>
        <ul>
            <li><strong>Datos de cuenta:</strong> Direcci&oacute;n de correo electr&oacute;nico y nombre (a trav&eacute;s de registro directo, Google Sign-In o Apple Sign-In) para autenticaci&oacute;n.</li>
            <li><strong>Datos financieros:</strong> Transacciones de ingresos y gastos que t&uacute; registras manualmente en la aplicaci&oacute;n (cantidades, categor&iacute;as, descripciones, fechas).</li>
            <li><strong>Audio:</strong> Grabaciones de voz temporales procesadas en el dispositivo para crear transacciones por voz. El audio no se almacena ni se env&iacute;a a servidores externos.</li>
            <li><strong>Fotos:</strong> Im&aacute;genes de recibos que t&uacute; captures o selecciones, procesadas para extraer datos de transacciones.</li>
            <li><strong>Datos de suscripci&oacute;n:</strong> Estado de tu suscripci&oacute;n PRO y historial de compras in-app.</li>
            <li><strong>Preferencias:</strong> Idioma, tema y configuraciones de la aplicaci&oacute;n, almacenadas localmente en tu dispositivo.</li>
        </ul>

        <h2>2. C&oacute;mo Usamos la Informaci&oacute;n</h2>
        <ul>
            <li>Proporcionar las funcionalidades de la aplicaci&oacute;n (registro de transacciones, gr&aacute;ficos, exportaci&oacute;n).</li>
            <li>Autenticar tu cuenta y proteger el acceso.</li>
            <li>Gestionar tu suscripci&oacute;n PRO.</li>
            <li>Almacenar tus datos de forma segura en nuestros servidores (Supabase).</li>
        </ul>

        <h2>3. Almacenamiento y Seguridad</h2>
        <p>Tus datos se almacenan en servidores seguros de Supabase con cifrado en tr&aacute;nsito (TLS/SSL) y en reposo. Las credenciales sensibles se guardan usando almacenamiento seguro del dispositivo (Keychain en iOS, EncryptedSharedPreferences en Android).</p>

        <h2>4. Compartici&oacute;n de Datos</h2>
        <p><strong>No vendemos, alquilamos ni compartimos tus datos personales con terceros</strong>, excepto:</p>
        <ul>
            <li><strong>Supabase:</strong> Proveedor de infraestructura para almacenamiento de datos.</li>
            <li><strong>Google/Apple:</strong> Para autenticaci&oacute;n y procesamiento de pagos in-app.</li>
            <li><strong>Requisitos legales:</strong> Cuando sea requerido por ley.</li>
        </ul>

        <h2>5. Rastreo y Publicidad</h2>
        <p>Expense Manager <strong>no utiliza rastreadores, anal&iacute;ticas de terceros ni publicidad dirigida</strong>. No recopilamos datos con fines publicitarios.</p>

        <h2>6. Tus Derechos</h2>
        <p>Tienes derecho a:</p>
        <ul>
            <li>Acceder a tus datos a trav&eacute;s de la aplicaci&oacute;n (exportaci&oacute;n a Excel).</li>
            <li>Solicitar la eliminaci&oacute;n de tu cuenta y todos tus datos.</li>
            <li>Retirar el consentimiento de permisos del dispositivo en cualquier momento desde los ajustes del sistema.</li>
        </ul>

        <h2>7. Retenci&oacute;n de Datos</h2>
        <p>Tus datos se mantienen mientras tu cuenta est&eacute; activa. Si eliminas tu cuenta, todos tus datos ser&aacute;n eliminados permanentemente en un plazo de 30 d&iacute;as.</p>

        <h2>8. Menores</h2>
        <p>Esta aplicaci&oacute;n no est&aacute; dirigida a menores de 13 a&ntilde;os. No recopilamos conscientemente datos de menores.</p>

        <h2>9. Cambios en esta Pol&iacute;tica</h2>
        <p>Podemos actualizar esta pol&iacute;tica de privacidad ocasionalmente. Te notificaremos de cambios significativos a trav&eacute;s de la aplicaci&oacute;n.</p>

        <h2>10. Contacto</h2>
        <p>Si tienes preguntas sobre esta pol&iacute;tica de privacidad, cont&aacute;ctanos en: <strong>[TU_EMAIL_DE_CONTACTO]</strong></p>
    </div>

    <!-- ENGLISH VERSION -->
    <div class="en">
        <h1>Expense Manager Privacy Policy</h1>
        <p class="effective-date">Effective date: March 18, 2026</p>

        <h2>1. Information We Collect</h2>
        <p>Expense Manager collects the following information to provide and improve the service:</p>
        <ul>
            <li><strong>Account data:</strong> Email address and name (via direct registration, Google Sign-In, or Apple Sign-In) for authentication.</li>
            <li><strong>Financial data:</strong> Income and expense transactions you manually enter in the app (amounts, categories, descriptions, dates).</li>
            <li><strong>Audio:</strong> Temporary voice recordings processed on-device to create voice transactions. Audio is not stored or sent to external servers.</li>
            <li><strong>Photos:</strong> Receipt images you capture or select, processed to extract transaction data.</li>
            <li><strong>Subscription data:</strong> Your PRO subscription status and in-app purchase history.</li>
            <li><strong>Preferences:</strong> Language, theme, and app settings, stored locally on your device.</li>
        </ul>

        <h2>2. How We Use Information</h2>
        <ul>
            <li>Provide app functionality (transaction logging, charts, export).</li>
            <li>Authenticate your account and protect access.</li>
            <li>Manage your PRO subscription.</li>
            <li>Store your data securely on our servers (Supabase).</li>
        </ul>

        <h2>3. Storage and Security</h2>
        <p>Your data is stored on secure Supabase servers with encryption in transit (TLS/SSL) and at rest. Sensitive credentials are stored using the device's secure storage (Keychain on iOS, EncryptedSharedPreferences on Android).</p>

        <h2>4. Data Sharing</h2>
        <p><strong>We do not sell, rent, or share your personal data with third parties</strong>, except:</p>
        <ul>
            <li><strong>Supabase:</strong> Infrastructure provider for data storage.</li>
            <li><strong>Google/Apple:</strong> For authentication and in-app payment processing.</li>
            <li><strong>Legal requirements:</strong> When required by law.</li>
        </ul>

        <h2>5. Tracking and Advertising</h2>
        <p>Expense Manager <strong>does not use third-party trackers, analytics, or targeted advertising</strong>. We do not collect data for advertising purposes.</p>

        <h2>6. Your Rights</h2>
        <p>You have the right to:</p>
        <ul>
            <li>Access your data through the app (Excel export).</li>
            <li>Request deletion of your account and all your data.</li>
            <li>Withdraw consent for device permissions at any time from system settings.</li>
        </ul>

        <h2>7. Data Retention</h2>
        <p>Your data is kept as long as your account is active. If you delete your account, all your data will be permanently deleted within 30 days.</p>

        <h2>8. Children</h2>
        <p>This app is not directed at children under 13. We do not knowingly collect data from minors.</p>

        <h2>9. Changes to this Policy</h2>
        <p>We may update this privacy policy from time to time. We will notify you of significant changes through the app.</p>

        <h2>10. Contact</h2>
        <p>If you have questions about this privacy policy, contact us at: <strong>[YOUR_CONTACT_EMAIL]</strong></p>
    </div>
</body>
</html>
