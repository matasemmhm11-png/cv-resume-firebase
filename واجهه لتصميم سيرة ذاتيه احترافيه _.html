<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>نظام السيرة الذاتية التفاعلي</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Cairo:wght@300;400;500;600;700;800&family=Tajawal:wght@300;400;500;700&display=swap" rel="stylesheet">
    <!-- Firebase SDK -->
    <script src="https://www.gstatic.com/firebasejs/9.22.0/firebase-app-compat.js"></script>
    <script src="https://www.gstatic.com/firebasejs/9.22.0/firebase-firestore-compat.js"></script>
    <script src="https://www.gstatic.com/firebasejs/9.22.0/firebase-auth-compat.js"></script>
    <script src="https://www.gstatic.com/firebasejs/9.22.0/firebase-storage-compat.js"></script>
    <!-- html2canvas for image export -->
    <script src="https://html2canvas.hertzen.com/dist/html2canvas.min.js"></script>
    <style>
        :root {
            --primary-color: #1a365d;
            --secondary-color: #2d3748;
            --accent-color: #2b6cb0;
            --success-color: #38a169;
            --danger-color: #e53e3e;
            --warning-color: #dd6b20;
            --light-color: #f7fafc;
            --dark-color: #1a202c;
            --gray-color: #4a5568;
            --border-radius: 8px;
            --box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            --transition: all 0.3s ease;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Tajawal', 'Cairo', sans-serif;
            line-height: 1.6;
            color: #2d3748;
            background-color: #f8f9fa;
            max-width: 1400px;
            margin: 0 auto;
            padding: 20px;
        }

        .app-container {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 30px;
            margin-top: 20px;
        }

        @media (max-width: 992px) {
            .app-container {
                grid-template-columns: 1fr;
            }
        }

        /* FORM STYLES */
        .form-container {
            background: white;
            border-radius: 15px;
            padding: 30px;
            box-shadow: var(--box-shadow);
            overflow-y: auto;
            max-height: 90vh;
        }

        .form-title {
            font-size: 1.8rem;
            font-weight: 800;
            color: var(--primary-color);
            margin-bottom: 25px;
            padding-bottom: 15px;
            border-bottom: 3px solid var(--accent-color);
            position: relative;
        }

        .form-group {
            margin-bottom: 25px;
        }

        .form-label {
            display: block;
            margin-bottom: 10px;
            font-weight: 600;
            color: var(--dark-color);
        }

        .form-input, .form-textarea, .form-select {
            width: 100%;
            padding: 14px;
            border: 2px solid #e2e8f0;
            border-radius: var(--border-radius);
            font-family: inherit;
            font-size: 1rem;
            transition: var(--transition);
            background: white;
        }

        .form-input:focus, .form-textarea:focus, .form-select:focus {
            outline: none;
            border-color: var(--accent-color);
            box-shadow: 0 0 0 3px rgba(43, 108, 176, 0.1);
        }

        .form-textarea {
            min-height: 120px;
            resize: vertical;
        }

        /* FORM SECTIONS */
        .form-section {
            margin-bottom: 35px;
            padding: 25px;
            background: var(--light-color);
            border-radius: var(--border-radius);
            border-right: 4px solid var(--accent-color);
        }

        body[dir="ltr"] .form-section {
            border-right: none;
            border-left: 4px solid var(--accent-color);
        }

        .section-title {
            font-size: 1.5rem;
            font-weight: 700;
            color: var(--primary-color);
            margin-bottom: 20px;
            display: flex;
            align-items: center;
            gap: 10px;
        }

        .section-title i {
            color: var(--accent-color);
        }

        /* DYNAMIC LISTS */
        .dynamic-list {
            margin-top: 15px;
        }

        .list-item {
            display: flex;
            gap: 15px;
            margin-bottom: 15px;
            padding: 15px;
            background: white;
            border-radius: var(--border-radius);
            border: 1px solid #e2e8f0;
        }

        .list-item-content {
            flex-grow: 1;
        }

        .btn-list {
            background: var(--accent-color);
            color: white;
            border: none;
            border-radius: var(--border-radius);
            padding: 8px 15px;
            cursor: pointer;
            font-weight: 600;
            transition: var(--transition);
            display: flex;
            align-items: center;
            gap: 8px;
        }

        .btn-list:hover {
            background: var(--primary-color);
        }

        .btn-danger {
            background: var(--danger-color);
        }

        .btn-danger:hover {
            background: #c53030;
        }

        /* BUTTONS */
        .action-buttons {
            display: flex;
            gap: 15px;
            margin-top: 30px;
            flex-wrap: wrap;
        }

        .btn {
            padding: 14px 25px;
            border: none;
            border-radius: var(--border-radius);
            cursor: pointer;
            font-weight: 600;
            transition: var(--transition);
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 10px;
            font-size: 1rem;
            flex: 1;
            min-width: 150px;
        }

        .btn-primary {
            background: var(--primary-color);
            color: white;
        }

        .btn-primary:hover {
            background: var(--secondary-color);
            transform: translateY(-3px);
            box-shadow: var(--box-shadow);
        }

        .btn-success {
            background: var(--success-color);
            color: white;
        }

        .btn-success:hover {
            background: #2f855a;
            transform: translateY(-3px);
            box-shadow: var(--box-shadow);
        }

        .btn-warning {
            background: var(--warning-color);
            color: white;
        }

        .btn-warning:hover {
            background: #c05621;
            transform: translateY(-3px);
            box-shadow: var(--box-shadow);
        }

        .btn-secondary {
            background: var(--gray-color);
            color: white;
        }

        .btn-secondary:hover {
            background: #4a5568;
            transform: translateY(-3px);
            box-shadow: var(--box-shadow);
        }

        /* PREVIEW SECTION */
        .preview-container {
            background: white;
            border-radius: 15px;
            padding: 30px;
            box-shadow: var(--box-shadow);
            overflow-y: auto;
            max-height: 90vh;
        }

        .preview-title {
            font-size: 1.8rem;
            font-weight: 800;
            color: var(--primary-color);
            margin-bottom: 25px;
            padding-bottom: 15px;
            border-bottom: 3px solid var(--accent-color);
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .preview-actions {
            display: flex;
            gap: 10px;
        }

        /* RESUME PREVIEW STYLES */
        .resume-preview {
            background: white;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
            min-height: 800px;
        }

        .resume-container {
            display: grid;
            grid-template-columns: 1fr 2fr;
            min-height: 800px;
        }

        .resume-sidebar {
            background: linear-gradient(180deg, var(--primary-color) 0%, var(--secondary-color) 100%);
            color: white;
            padding: 40px 30px;
        }

        .resume-main {
            padding: 40px 35px;
        }

        .profile-img-container {
            text-align: center;
            margin-bottom: 30px;
        }

        .profile-img-preview {
            width: 180px;
            height: 180px;
            border-radius: 50%;
            border: 5px solid rgba(255, 255, 255, 0.2);
            object-fit: cover;
            margin: 0 auto 20px;
            background: linear-gradient(135deg, #4c86a8, #3a506b);
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            font-size: 3rem;
        }

        .preview-name {
            font-size: 2.2rem;
            font-weight: 700;
            margin-bottom: 10px;
            color: white;
        }

        .preview-title {
            font-size: 1.3rem;
            color: #cbd5e0;
            margin-bottom: 25px;
            padding-bottom: 15px;
            border-bottom: 2px solid rgba(255, 255, 255, 0.1);
        }

        .preview-section {
            margin-bottom: 35px;
        }

        .preview-section-title {
            font-size: 1.5rem;
            font-weight: 700;
            margin-bottom: 20px;
            color: white;
            padding-bottom: 10px;
            border-bottom: 2px solid rgba(255, 255, 255, 0.2);
            position: relative;
        }

        .preview-section-title:after {
            content: '';
            position: absolute;
            bottom: -2px;
            right: 0;
            width: 60px;
            height: 2px;
            background: var(--accent-color);
        }

        body[dir="ltr"] .preview-section-title:after {
            right: auto;
            left: 0;
        }

        .preview-contact-item {
            display: flex;
            align-items: center;
            margin-bottom: 15px;
            padding: 12px 15px;
            background: rgba(255, 255, 255, 0.1);
            border-radius: var(--border-radius);
        }

        .preview-contact-icon {
            font-size: 1.2rem;
            margin-left: 15px;
            width: 25px;
            text-align: center;
        }

        body[dir="ltr"] .preview-contact-icon {
            margin-left: 0;
            margin-right: 15px;
        }

        .preview-skill-item, .preview-language-item {
            margin-bottom: 15px;
            padding: 10px 15px;
            background: rgba(255, 255, 255, 0.05);
            border-radius: var(--border-radius);
        }

        .preview-skill-name {
            display: block;
            margin-bottom: 8px;
            font-weight: 600;
        }

        .preview-skill-bar {
            height: 8px;
            background: rgba(255, 255, 255, 0.1);
            border-radius: 4px;
            overflow: hidden;
        }

        .preview-skill-level {
            height: 100%;
            background: var(--accent-color);
            border-radius: 4px;
        }

        /* MAIN PREVIEW CONTENT */
        .main-preview-title {
            font-size: 1.8rem;
            font-weight: 800;
            color: var(--primary-color);
            margin-bottom: 25px;
            padding-bottom: 15px;
            border-bottom: 3px solid var(--accent-color);
            position: relative;
        }

        .preview-experience-item, .preview-education-item {
            margin-bottom: 25px;
            padding: 20px;
            background: var(--light-color);
            border-radius: var(--border-radius);
            border-right: 4px solid var(--accent-color);
        }

        body[dir="ltr"] .preview-experience-item,
        body[dir="ltr"] .preview-education-item {
            border-right: none;
            border-left: 4px solid var(--accent-color);
        }

        .preview-experience-header, .preview-education-header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 15px;
            flex-wrap: wrap;
        }

        .preview-experience-title, .preview-education-degree {
            font-size: 1.4rem;
            font-weight: 700;
            color: var(--primary-color);
        }

        .preview-experience-period, .preview-education-period {
            background: var(--accent-color);
            color: white;
            padding: 5px 15px;
            border-radius: 20px;
            font-size: 0.9rem;
            font-weight: 600;
        }

        /* NOTIFICATIONS */
        .notification {
            position: fixed;
            top: 20px;
            right: 20px;
            padding: 15px 25px;
            border-radius: var(--border-radius);
            color: white;
            font-weight: 600;
            z-index: 1000;
            display: flex;
            align-items: center;
            gap: 10px;
            transform: translateX(150%);
            transition: transform 0.5s ease;
            max-width: 400px;
        }

        .notification.show {
            transform: translateX(0);
        }

        .notification-success {
            background: var(--success-color);
        }

        .notification-error {
            background: var(--danger-color);
        }

        .notification-warning {
            background: var(--warning-color);
        }

        /* LOADING */
        .loading-overlay {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0, 0, 0, 0.7);
            display: flex;
            justify-content: center;
            align-items: center;
            z-index: 2000;
            display: none;
        }

        .loading-overlay.active {
            display: flex;
        }

        .spinner {
            width: 50px;
            height: 50px;
            border: 5px solid rgba(255, 255, 255, 0.3);
            border-radius: 50%;
            border-top-color: white;
            animation: spin 1s ease-in-out infinite;
        }

        @keyframes spin {
            to { transform: rotate(360deg); }
        }

        /* IMAGE UPLOAD */
        .image-upload-container {
            text-align: center;
            margin-bottom: 25px;
        }

        .image-upload-label {
            display: inline-block;
            padding: 15px 30px;
            background: var(--light-color);
            border-radius: var(--border-radius);
            border: 2px dashed var(--accent-color);
            cursor: pointer;
            transition: var(--transition);
            width: 100%;
        }

        .image-upload-label:hover {
            background: #e2e8f0;
        }

        .upload-icon {
            font-size: 3rem;
            color: var(--accent-color);
            margin-bottom: 15px;
        }

        .image-preview-container {
            margin-top: 20px;
        }

        .image-preview {
            max-width: 200px;
            max-height: 200px;
            border-radius: 50%;
            border: 3px solid var(--accent-color);
            object-fit: cover;
            margin: 0 auto;
            display: block;
        }

        /* RESPONSIVE */
        @media (max-width: 768px) {
            .resume-container {
                grid-template-columns: 1fr;
            }
            
            .resume-sidebar {
                padding: 25px;
            }
            
            .resume-main {
                padding: 25px;
            }
            
            .action-buttons {
                flex-direction: column;
            }
            
            .btn {
                width: 100%;
            }
            
            .preview-actions {
                flex-direction: column;
                width: 100%;
            }
        }

        @media (max-width: 576px) {
            .form-container, .preview-container {
                padding: 20px;
            }
            
            .form-section {
                padding: 15px;
            }
            
            .preview-name {
                font-size: 1.8rem;
            }
            
            .preview-experience-header, .preview-education-header {
                flex-direction: column;
                align-items: flex-start;
                gap: 10px;
            }
        }
    </style>
</head>
<body dir="rtl">
    <!-- NOTIFICATION SYSTEM -->
    <div id="notification" class="notification">
        <i class="fas fa-info-circle"></i>
        <span id="notification-text"></span>
    </div>

    <!-- LOADING OVERLAY -->
    <div class="loading-overlay" id="loadingOverlay">
        <div class="spinner"></div>
    </div>

    <!-- APP HEADER -->
    <header style="text-align: center; margin-bottom: 30px;">
        <h1 style="font-size: 2.5rem; color: var(--primary-color); margin-bottom: 10px;">
            <i class="fas fa-file-contract"></i> نظام السيرة الذاتية التفاعلي
        </h1>
        <p style="color: var(--gray-color); font-size: 1.1rem;">
            قم بتعبئة البيانات، احفظها في قاعدة البيانات، واطبع سيرتك الذاتية كملف PDF أو صورة
        </p>
    </header>

    <!-- MAIN APP CONTAINER -->
    <div class="app-container">
        <!-- FORM SECTION -->
        <div class="form-container">
            <h2 class="form-title">
                <i class="fas fa-edit"></i> تعبئة بيانات السيرة الذاتية
            </h2>

            <!-- PERSONAL INFO SECTION -->
            <div class="form-section">
                <h3 class="section-title">
                    <i class="fas fa-user"></i> المعلومات الشخصية
                </h3>
                
                <div class="image-upload-container">
                    <label class="image-upload-label" for="profileImage">
                        <div class="upload-icon">
                            <i class="fas fa-camera"></i>
                        </div>
                        <div>انقر لرفع صورة شخصية</div>
                        <input type="file" id="profileImage" accept="image/*" style="display: none;">
                    </label>
                    <div class="image-preview-container">
                        <img id="imagePreview" class="image-preview" src="" alt="صورة المعاينة" style="display: none;">
                    </div>
                </div>

                <div class="form-group">
                    <label class="form-label" for="fullName">الاسم الكامل</label>
                    <input type="text" id="fullName" class="form-input" placeholder="أدخل اسمك الكامل">
                </div>

                <div class="form-group">
                    <label class="form-label" for="jobTitle">المسمى الوظيفي</label>
                    <input type="text" id="jobTitle" class="form-input" placeholder="أدخل المسمى الوظيفي">
                </div>

                <div class="form-group">
                    <label class="form-label" for="email">البريد الإلكتروني</label>
                    <input type="email" id="email" class="form-input" placeholder="example@email.com">
                </div>

                <div class="form-group">
                    <label class="form-label" for="phone">رقم الهاتف</label>
                    <input type="tel" id="phone" class="form-input" placeholder="+966 5X XXX XXXX">
                </div>

                <div class="form-group">
                    <label class="form-label" for="location">العنوان</label>
                    <input type="text" id="location" class="form-input" placeholder="المدينة، الدولة">
                </div>

                <div class="form-group">
                    <label class="form-label" for="summary">ملخص الملف الشخصي</label>
                    <textarea id="summary" class="form-textarea" placeholder="اكتب ملخصاً عن خبراتك ومهاراتك..."></textarea>
                </div>
            </div>

            <!-- EXPERIENCE SECTION -->
            <div class="form-section">
                <h3 class="section-title">
                    <i class="fas fa-briefcase"></i> الخبرات العملية
                </h3>
                
                <div id="experienceList">
                    <!-- Dynamic experience items will be added here -->
                </div>
                
                <button class="btn-list" onclick="addExperience()">
                    <i class="fas fa-plus"></i> إضافة خبرة جديدة
                </button>
            </div>

            <!-- EDUCATION SECTION -->
            <div class="form-section">
                <h3 class="section-title">
                    <i class="fas fa-graduation-cap"></i> التعليم
                </h3>
                
                <div id="educationList">
                    <!-- Dynamic education items will be added here -->
                </div>
                
                <button class="btn-list" onclick="addEducation()">
                    <i class="fas fa-plus"></i> إضافة مؤهل تعليمي
                </button>
            </div>

            <!-- SKILLS SECTION -->
            <div class="form-section">
                <h3 class="section-title">
                    <i class="fas fa-tools"></i> المهارات
                </h3>
                
                <div id="skillsList">
                    <!-- Dynamic skill items will be added here -->
                </div>
                
                <button class="btn-list" onclick="addSkill()">
                    <i class="fas fa-plus"></i> إضافة مهارة جديدة
                </button>
            </div>

            <!-- LANGUAGES SECTION -->
            <div class="form-section">
                <h3 class="section-title">
                    <i class="fas fa-language"></i> اللغات
                </h3>
                
                <div id="languagesList">
                    <!-- Dynamic language items will be added here -->
                </div>
                
                <button class="btn-list" onclick="addLanguage()">
                    <i class="fas fa-plus"></i> إضافة لغة جديدة
                </button>
            </div>

            <!-- ACTION BUTTONS -->
            <div class="action-buttons">
                <button class="btn btn-primary" onclick="saveResume()">
                    <i class="fas fa-save"></i> حفظ السيرة الذاتية
                </button>
                <button class="btn btn-success" onclick="updateResume()">
                    <i class="fas fa-edit"></i> تحديث البيانات
                </button>
                <button class="btn btn-warning" onclick="loadResume()">
                    <i class="fas fa-download"></i> تحميل البيانات
                </button>
                <button class="btn btn-secondary" onclick="clearForm()">
                    <i class="fas fa-trash"></i> مسح النموذج
                </button>
            </div>
        </div>

        <!-- PREVIEW SECTION -->
        <div class="preview-container">
            <div class="preview-title">
                <span><i class="fas fa-eye"></i> معاينة السيرة الذاتية</span>
                <div class="preview-actions">
                    <button class="btn btn-primary" onclick="printResume()" style="padding: 10px 15px;">
                        <i class="fas fa-print"></i> طباعة
                    </button>
                    <button class="btn btn-success" onclick="exportAsImage()" style="padding: 10px 15px;">
                        <i class="fas fa-image"></i> حفظ كصورة
                    </button>
                </div>
            </div>

            <div class="resume-preview" id="resumePreview">
                <!-- Resume content will be dynamically generated here -->
                <div class="resume-container" id="resumeContainer">
                    <div class="resume-sidebar">
                        <div class="profile-img-container">
                            <div id="previewProfileImage" class="profile-img-preview">
                                <i class="fas fa-user"></i>
                            </div>
                            <h2 id="previewName" class="preview-name">الاسم الكامل</h2>
                            <p id="previewTitle" class="preview-title">المسمى الوظيفي</p>
                        </div>

                        <div class="preview-section">
                            <h3 class="preview-section-title">معلومات الاتصال</h3>
                            <div id="previewContactInfo">
                                <!-- Contact info will be added here -->
                            </div>
                        </div>

                        <div class="preview-section">
                            <h3 class="preview-section-title">المهارات</h3>
                            <div id="previewSkills">
                                <!-- Skills will be added here -->
                            </div>
                        </div>

                        <div class="preview-section">
                            <h3 class="preview-section-title">اللغات</h3>
                            <div id="previewLanguages">
                                <!-- Languages will be added here -->
                            </div>
                        </div>
                    </div>

                    <div class="resume-main">
                        <div class="preview-section">
                            <h2 class="main-preview-title">الملف الشخصي</h2>
                            <p id="previewSummary" style="color: var(--gray-color); text-align: justify;">
                                ملخص الملف الشخصي سيظهر هنا...
                            </p>
                        </div>

                        <div class="preview-section">
                            <h2 class="main-preview-title">الخبرات العملية</h2>
                            <div id="previewExperiences">
                                <!-- Experiences will be added here -->
                            </div>
                        </div>

                        <div class="preview-section">
                            <h2 class="main-preview-title">التعليم</h2>
                            <div id="previewEducation">
                                <!-- Education will be added here -->
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!-- FIREBASE INIT & APP JS -->
    <script>
        // ==================== FIREBASE CONFIGURATION ====================
        // TODO: Replace with your Firebase project configuration
        const firebaseConfig = {
         apiKey: "AIzaSyC_P4zgLJScHi-VyQcC5PX0kHvaL1BHxI4",
        authDomain: "cv-resume-app-c7417.firebaseapp.com",
        projectId: "cv-resume-app-c7417",
        storageBucket: "cv-resume-app-c7417.firebasestorage.app",
        messagingSenderId: "850611310974",
        appId: "1:850611310974:web:66c8cbd81805b64539e32f"
};


        // Initialize Firebase
        firebase.initializeApp(firebaseConfig);
        const db = firebase.firestore();
        const storage = firebase.storage();
        const auth = firebase.auth();

        // ==================== GLOBAL VARIABLES ====================
        let currentUser = null;
        let currentResumeId = null;
        let uploadedImageUrl = null;

        // ==================== AUTHENTICATION ====================
        // Simple anonymous authentication for demo
        auth.signInAnonymously()
            .then(() => {
                auth.onAuthStateChanged((user) => {
                    if (user) {
                        currentUser = user;
                        showNotification("تم الاتصال بقاعدة البيانات بنجاح", "success");
                        loadUserResumes();
                    }
                });
            })
            .catch((error) => {
                console.error("Authentication error:", error);
                showNotification("خطأ في المصادقة، سيتم استخدام التخزين المحلي", "error");
            });

        // ==================== NOTIFICATION SYSTEM ====================
        function showNotification(message, type = "success") {
            const notification = document.getElementById('notification');
            const notificationText = document.getElementById('notification-text');
            
            notificationText.textContent = message;
            notification.className = `notification notification-${type} show`;
            
            setTimeout(() => {
                notification.classList.remove('show');
            }, 3000);
        }

        // ==================== LOADING OVERLAY ====================
        function showLoading() {
            document.getElementById('loadingOverlay').classList.add('active');
        }

        function hideLoading() {
            document.getElementById('loadingOverlay').classList.remove('active');
        }

        // ==================== IMAGE UPLOAD HANDLING ====================
        document.getElementById('profileImage').addEventListener('change', function(e) {
            const file = e.target.files[0];
            if (file) {
                const reader = new FileReader();
                reader.onload = function(e) {
                    const imagePreview = document.getElementById('imagePreview');
                    imagePreview.src = e.target.result;
                    imagePreview.style.display = 'block';
                    
                    // Update preview
                    document.getElementById('previewProfileImage').innerHTML = 
                        `<img src="${e.target.result}" alt="صورة الملف الشخصي" style="width: 100%; height: 100%; border-radius: 50%; object-fit: cover;">`;
                };
                reader.readAsDataURL(file);
                
                // Upload to Firebase Storage
                uploadImageToStorage(file);
            }
        });

        function uploadImageToStorage(file) {
            showLoading();
            const storageRef = storage.ref();
            const imageRef = storageRef.child(`profile-images/${currentUser.uid}/${Date.now()}_${file.name}`);
            
            imageRef.put(file)
                .then((snapshot) => {
                    return snapshot.ref.getDownloadURL();
                })
                .then((url) => {
                    uploadedImageUrl = url;
                    hideLoading();
                    showNotification("تم رفع الصورة بنجاح", "success");
                })
                .catch((error) => {
                    hideLoading();
                    showNotification("خطأ في رفع الصورة", "error");
                    console.error("Upload error:", error);
                });
        }

        // ==================== DYNAMIC FORM ELEMENTS ====================
        // Experience template
        function addExperience(experience = { title: '', company: '', period: '', description: '' }) {
            const experienceList = document.getElementById('experienceList');
            const id = 'exp_' + Date.now();
            
            const experienceHtml = `
                <div class="list-item" id="${id}">
                    <div class="list-item-content">
                        <input type="text" class="form-input" placeholder="المسمى الوظيفي" 
                               value="${experience.title}" onchange="updatePreview()">
                        <input type="text" class="form-input" placeholder="اسم الشركة" 
                               value="${experience.company}" onchange="updatePreview()">
                        <input type="text" class="form-input" placeholder="فترة العمل (مثال: 2020-2023)" 
                               value="${experience.period}" onchange="updatePreview()">
                        <textarea class="form-textarea" placeholder="الوصف والمهام" 
                                  onchange="updatePreview()">${experience.description}</textarea>
                    </div>
                    <button class="btn-list btn-danger" onclick="removeElement('${id}')">
                        <i class="fas fa-trash"></i>
                    </button>
                </div>
            `;
            
            experienceList.insertAdjacentHTML('beforeend', experienceHtml);
            updatePreview();
        }

        // Education template
        function addEducation(education = { degree: '', institution: '', period: '', description: '' }) {
            const educationList = document.getElementById('educationList');
            const id = 'edu_' + Date.now();
            
            const educationHtml = `
                <div class="list-item" id="${id}">
                    <div class="list-item-content">
                        <input type="text" class="form-input" placeholder="المؤهل الدراسي" 
                               value="${education.degree}" onchange="updatePreview()">
                        <input type="text" class="form-input" placeholder="اسم المؤسسة التعليمية" 
                               value="${education.institution}" onchange="updatePreview()">
                        <input type="text" class="form-input" placeholder="سنة التخرج" 
                               value="${education.period}" onchange="updatePreview()">
                        <textarea class="form-textarea" placeholder="التفاصيل" 
                                  onchange="updatePreview()">${education.description}</textarea>
                    </div>
                    <button class="btn-list btn-danger" onclick="removeElement('${id}')">
                        <i class="fas fa-trash"></i>
                    </button>
                </div>
            `;
            
            educationList.insertAdjacentHTML('beforeend', educationHtml);
            updatePreview();
        }

        // Skill template dd
        function addSkill(skill = { name: '', level: 50 }) {
            const skillsList = document.getElementById('skillsList');
            const id = 'skill_' + Date.now();
            
            const skillHtml = `
                <div class="list-item" id="${id}">
                    <div class="list-item-content">
                        <input type="text" class="form-input" placeholder="اسم المهارة" 
                               value="${skill.name}" onchange="updatePreview()">
                        <input type="range" class="form-input" min="0" max="100" value="${skill.level}" 
                               onchange="updatePreview()" style="padding: 0;">
                        <span>${skill.level}%</span>
                    </div>
                    <button class="btn-list btn-danger" onclick="removeElement('${id}')">
                        <i class="fas fa-trash"></i>
                    </button>
                </div>
            `;
            
            skillsList.insertAdjacentHTML('beforeend', skillHtml);
            updatePreview();
        }

        // Language template
        function addLanguage(language = { name: '', level: '' }) {
            const languagesList = document.getElementById('languagesList');
            const id = 'lang_' + Date.now();
            
            const languageHtml = `
                <div class="list-item" id="${id}">
                    <div class="list-item-content">
                        <input type="text" class="form-input" placeholder="اسم اللغة" 
                               value="${language.name}" onchange="updatePreview()">
                        <select class="form-select" onchange="updatePreview()">
                            <option value="مبتدئ" ${language.level === 'مبتدئ' ? 'selected' : ''}>مبتدئ</option>
                            <option value="متوسط" ${language.level === 'متوسط' ? 'selected' : ''}>متوسط</option>
                            <option value="متقدم" ${language.level === 'متقدم' ? 'selected' : ''}>متقدم</option>
                            <option value="اللغة الأم" ${language.level === 'اللغة الأم' ? 'selected' : ''}>اللغة الأم</option>
                        </select>
                    </div>
                    <button class="btn-list btn-danger" onclick="removeElement('${id}')">
                        <i class="fas fa-trash"></i>
                    </button>
                </div>
            `;
            
            languagesList.insertAdjacentHTML('beforeend', languageHtml);
            updatePreview();
        }

        function removeElement(id) {
            document.getElementById(id).remove();
            updatePreview();
        }

        // ==================== FORM DATA COLLECTION ====================
        function collectFormData() {
            const formData = {
                personalInfo: {
                    fullName: document.getElementById('fullName').value,
                    jobTitle: document.getElementById('jobTitle').value,
                    email: document.getElementById('email').value,
                    phone: document.getElementById('phone').value,
                    location: document.getElementById('location').value,
                    summary: document.getElementById('summary').value,
                    profileImage: uploadedImageUrl
                },
                experiences: [],
                education: [],
                skills: [],
                languages: [],
                createdAt: new Date().toISOString(),
                updatedAt: new Date().toISOString(),
                userId: currentUser ? currentUser.uid : 'anonymous'
            };

            // Collect experiences
            document.querySelectorAll('#experienceList .list-item').forEach(item => {
                const inputs = item.querySelectorAll('input, textarea');
                formData.experiences.push({
                    title: inputs[0].value,
                    company: inputs[1].value,
                    period: inputs[2].value,
                    description: inputs[3].value
                });
            });

            // Collect education
            document.querySelectorAll('#educationList .list-item').forEach(item => {
                const inputs = item.querySelectorAll('input, textarea');
                formData.education.push({
                    degree: inputs[0].value,
                    institution: inputs[1].value,
                    period: inputs[2].value,
                    description: inputs[3].value
                });
            });

            // Collect skills
            document.querySelectorAll('#skillsList .list-item').forEach(item => {
                const inputs = item.querySelectorAll('input');
                formData.skills.push({
                    name: inputs[0].value,
                    level: parseInt(inputs[1].value) || 50
                });
            });

            // Collect languages
            document.querySelectorAll('#languagesList .list-item').forEach(item => {
                const inputs = item.querySelectorAll('input, select');
                formData.languages.push({
                    name: inputs[0].value,
                    level: inputs[1].value
                });
            });

            return formData;
        }

        // ==================== FIREBASE OPERATIONS ====================
        function saveResume() {
            const formData = collectFormData();
            
            if (!formData.personalInfo.fullName) {
                showNotification("الرجاء إدخال الاسم الكامل", "error");
                return;
            }

            showLoading();
            
            db.collection('resumes').add(formData)
                .then((docRef) => {
                    currentResumeId = docRef.id;
                    hideLoading();
                    showNotification("تم حفظ السيرة الذاتية بنجاح", "success");
                    loadUserResumes();
                })
                .catch((error) => {
                    hideLoading();
                    showNotification("خطأ في حفظ البيانات", "error");
                    console.error("Save error:", error);
                });
        }

        function updateResume() {
            if (!currentResumeId) {
                showNotification("لا يوجد سيرة ذاتية محفوظة للتحديث", "error");
                return;
            }

            const formData = collectFormData();
            formData.updatedAt = new Date().toISOString();

            showLoading();
            
            db.collection('resumes').doc(currentResumeId).update(formData)
                .then(() => {
                    hideLoading();
                    showNotification("تم تحديث السيرة الذاتية بنجاح", "success");
                })
                .catch((error) => {
                    hideLoading();
                    showNotification("خطأ في تحديث البيانات", "error");
                    console.error("Update error:", error);
                });
        }

        function loadResume() {
            showLoading();
            
            db.collection('resumes')
                .where('userId', '==', currentUser.uid)
                .orderBy('createdAt', 'desc')
                .limit(1)
                .get()
                .then((querySnapshot) => {
                    hideLoading();
                    
                    if (!querySnapshot.empty) {
                        const doc = querySnapshot.docs[0];
                        currentResumeId = doc.id;
                        const data = doc.data();
                        populateForm(data);
                        showNotification("تم تحميل بيانات السيرة الذاتية", "success");
                    } else {
                        showNotification("لا توجد سيرة ذاتية محفوظة", "warning");
                    }
                })
                .catch((error) => {
                    hideLoading();
                    showNotification("خطأ في تحميل البيانات", "error");
                    console.error("Load error:", error);
                });
        }

        function loadUserResumes() {
            if (!currentUser) return;
            
            db.collection('resumes')
                .where('userId', '==', currentUser.uid)
                .orderBy('createdAt', 'desc')
                .get()
                .then((querySnapshot) => {
                    if (!querySnapshot.empty) {
                        const doc = querySnapshot.docs[0];
                        currentResumeId = doc.id;
                        const data = doc.data();
                        populateForm(data);
                    }
                })
                .catch((error) => {
                    console.error("Load user resumes error:", error);
                });
        }

        // ==================== FORM POPULATION ====================
        function populateForm(data) {
            // Personal Info
            document.getElementById('fullName').value = data.personalInfo.fullName || '';
            document.getElementById('jobTitle').value = data.personalInfo.jobTitle || '';
            document.getElementById('email').value = data.personalInfo.email || '';
            document.getElementById('phone').value = data.personalInfo.phone || '';
            document.getElementById('location').value = data.personalInfo.location || '';
            document.getElementById('summary').value = data.personalInfo.summary || '';
            
            if (data.personalInfo.profileImage) {
                uploadedImageUrl = data.personalInfo.profileImage;
                document.getElementById('imagePreview').src = data.personalInfo.profileImage;
                document.getElementById('imagePreview').style.display = 'block';
                document.getElementById('previewProfileImage').innerHTML = 
                    `<img src="${data.personalInfo.profileImage}" alt="صورة الملف الشخصي" style="width: 100%; height: 100%; border-radius: 50%; object-fit: cover;">`;
            }

            // Clear existing dynamic lists
            document.getElementById('experienceList').innerHTML = '';
            document.getElementById('educationList').innerHTML = '';
            document.getElementById('skillsList').innerHTML = '';
            document.getElementById('languagesList').innerHTML = '';

            // Populate experiences
            if (data.experiences) {
                data.experiences.forEach(exp => addExperience(exp));
            }

            // Populate education
            if (data.education) {
                data.education.forEach(edu => addEducation(edu));
            }

            // Populate skills
            if (data.skills) {
                data.skills.forEach(skill => addSkill(skill));
            }

            // Populate languages
            if (data.languages) {
                data.languages.forEach(lang => addLanguage(lang));
            }

            updatePreview();
        }

        // ==================== PREVIEW UPDATE ====================
        function updatePreview() {
            const data = collectFormData();
            
            // Update personal info in preview
            document.getElementById('previewName').textContent = data.personalInfo.fullName || 'الاسم الكامل';
            document.getElementById('previewTitle').textContent = data.personalInfo.jobTitle || 'المسمى الوظيفي';
            document.getElementById('previewSummary').textContent = data.personalInfo.summary || 'ملخص الملف الشخصي سيظهر هنا...';
            
            // Update contact info
            const contactHtml = `
                <div class="preview-contact-item">
                    <i class="fas fa-envelope preview-contact-icon"></i>
                    <span>${data.personalInfo.email || 'example@email.com'}</span>
                </div>
                <div class="preview-contact-item">
                    <i class="fas fa-phone preview-contact-icon"></i>
                    <span>${data.personalInfo.phone || '+967 777777777'}</span>
                </div>
                <div class="preview-contact-item">
                    <i class="fas fa-map-marker-alt preview-contact-icon"></i>
                    <span>${data.personalInfo.location || 'المدينة، الدولة'}</span>
                </div>
            `;
            document.getElementById('previewContactInfo').innerHTML = contactHtml;
            
            // Update skills preview
            let skillsHtml = '';
            data.skills.forEach(skill => {
                skillsHtml += `
                    <div class="preview-skill-item">
                        <span class="preview-skill-name">${skill.name || 'المهارة'}</span>
                        <div class="preview-skill-bar">
                            <div class="preview-skill-level" style="width: ${skill.level}%"></div>
                        </div>
                    </div>
                `;
            });
            document.getElementById('previewSkills').innerHTML = skillsHtml || '<p>لا توجد مهارات مضافة</p>';
            
            // Update languages preview
            let languagesHtml = '';
            data.languages.forEach(lang => {
                languagesHtml += `
                    <div class="preview-language-item">
                        <strong>${lang.name || 'اللغة'}:</strong> ${lang.level || 'مستوى'}
                    </div>
                `;
            });
            document.getElementById('previewLanguages').innerHTML = languagesHtml || '<p>لا توجد لغات مضافة</p>';
            
            // Update experiences preview
            let experiencesHtml = '';
            data.experiences.forEach(exp => {
                experiencesHtml += `
                    <div class="preview-experience-item">
                        <div class="preview-experience-header">
                            <h3 class="preview-experience-title">${exp.title || 'المسمى الوظيفي'}</h3>
                            <span class="preview-experience-period">${exp.period || 'الفترة'}</span>
                        </div>
                        <p><strong>${exp.company || 'الشركة'}</strong></p>
                        <p>${exp.description || 'الوصف'}</p>
                    </div>
                `;
            });
            document.getElementById('previewExperiences').innerHTML = experiencesHtml || '<p>لا توجد خبرات مضافة</p>';
            
            // Update education preview
            let educationHtml = '';
            data.education.forEach(edu => {
                educationHtml += `
                    <div class="preview-education-item">
                        <div class="preview-education-header">
                            <h3 class="preview-education-degree">${edu.degree || 'المؤهل'}</h3>
                            <span class="preview-education-period">${edu.period || 'السنة'}</span>
                        </div>
                        <p><strong>${edu.institution || 'المؤسسة'}</strong></p>
                        <p>${edu.description || 'التفاصيل'}</p>
                    </div>
                `;
            });
            document.getElementById('previewEducation').innerHTML = educationHtml || '<p>لا توجد مؤهلات مضافة</p>';
        }

        // ==================== EXPORT FUNCTIONS ====================
        function printResume() {
            showLoading();
            
            // Create a print-friendly version
            const printContent = document.getElementById('resumePreview').innerHTML;
            const originalContent = document.body.innerHTML;
            
            document.body.innerHTML = `
                <!DOCTYPE html>
                <html dir="rtl">
                <head>
                    <meta charset="UTF-8">
                    <title>السيرة الذاتية - ${document.getElementById('fullName').value || 'مجهول'}</title>
                    <style>
                        body { font-family: 'Cairo', sans-serif; line-height: 1.6; padding: 20px; }
                        @media print {
                            @page { size: A4; margin: 0; }
                            body { margin: 1.6cm; }
                        }
                    </style>
                </head>
                <body>
                    ${printContent}
                    <script>
                        window.onload = function() {
                            window.print();
                            setTimeout(function() {
                                window.close();
                            }, 100);
                        }
                    <\/script>
                </body>
                </html>
            `;
            
            hideLoading();
        }

        function exportAsImage() {
            showLoading();
            
            html2canvas(document.getElementById('resumePreview'), {
                scale: 2,
                useCORS: true,
                logging: false,
                backgroundColor: '#ffffff'
            }).then(canvas => {
                const link = document.createElement('a');
                link.download = `سيرة_ذاتية_${document.getElementById('fullName').value || 'مجهول'}_${Date.now()}.png`;
                link.href = canvas.toDataURL('image/png');
                link.click();
                hideLoading();
                showNotification("تم حفظ السيرة الذاتية كصورة", "success");
            }).catch(error => {
                hideLoading();
                showNotification("خطأ في حفظ الصورة", "error");
                console.error("Export error:", error);
            });
        }

        // ==================== UTILITY FUNCTIONS ====================
        function clearForm() {
            if (confirm("هل أنت متأكد من مسح جميع البيانات؟")) {
                // Clear all form fields
                document.getElementById('fullName').value = '';
                document.getElementById('jobTitle').value = '';
                document.getElementById('email').value = '';
                document.getElementById('phone').value = '';
                document.getElementById('location').value = '';
                document.getElementById('summary').value = '';
                
                // Clear image preview
                document.getElementById('imagePreview').src = '';
                document.getElementById('imagePreview').style.display = 'none';
                document.getElementById('previewProfileImage').innerHTML = '<i class="fas fa-user"></i>';
                uploadedImageUrl = null;
                
                // Clear dynamic lists
                document.getElementById('experienceList').innerHTML = '';
                document.getElementById('educationList').innerHTML = '';
                document.getElementById('skillsList').innerHTML = '';
                document.getElementById('languagesList').innerHTML = '';
                
                // Reset resume ID
                currentResumeId = null;
                
                updatePreview();
                showNotification("تم مسح النموذج بنجاح", "success");
            }
        }

        // ==================== INITIAL SETUP ====================
        // Add initial empty items
        document.addEventListener('DOMContentLoaded', function() {
            addExperience();
            addEducation();
            addSkill();
            addLanguage();
            updatePreview();
        });

        // Update preview on any input change
        document.addEventListener('input', function(e) {
            if (e.target.tagName === 'INPUT' || e.target.tagName === 'TEXTAREA' || e.target.tagName === 'SELECT') {
                updatePreview();
            }
        });
    </script>
</body>
<footer style="
    text-align: center;
    margin-top: 30px;
    padding: 15px;
    color: #4a5568;
    font-size: 0.95rem;
    border-top: 1px solid #e2e8f0;
">
  © جميع الحقوق محفوظة — الطالب: <strong>م/معتصم العاسي </strong>  
  | للتواصل: <a href="matasemmhm11@gmail.com" style="color:#2b6cb0;">matasemmhm11@gmail.com</a>
</footer>

</html>
