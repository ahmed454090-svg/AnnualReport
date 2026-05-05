<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FTCF | Professional Dashboard</title>
    <link href="https://fonts.googleapis.com/css2?family=Noto+Nastaliq+Urdu:wght@400;700&family=Poppins:wght@400;600;700&display=swap" rel="stylesheet">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <style>
        body { background-color: #f0f2f5; font-family: 'Poppins', sans-serif; color: #1a1a1a; }
        .header-section { background: linear-gradient(135deg, #0f2027, #2c5364); color: white; padding: 50px 20px; text-align: center; border-radius: 0 0 40px 40px; position: relative; }
        
        /* Logo Styling */
        .logo-box { width: 80px; height: 80px; background: white; border-radius: 50%; margin: 0 auto 15px; display: flex; align-items: center; justify-content: center; border: 3px solid #e17055; overflow: hidden; box-shadow: 0 5px 15px rgba(0,0,0,0.2); }
        .logo-box span { color: #0f2027; font-weight: 700; font-size: 1.2rem; }

        .urdu-text { font-family: 'Noto Nastaliq Urdu', serif; line-height: 2.5; direction: rtl; }
        
        .section-title { font-size: 0.85rem; font-weight: 700; color: #2c5364; text-transform: uppercase; letter-spacing: 1px; margin-bottom: 15px; }
        
        /* Stats Cards */
        .stat-card { border: none; border-radius: 15px; padding: 15px; transition: 0.3s; background: white; border-left: 5px solid #2c5364; height: 100%; }
        .stat-label { font-size: 0.65rem; text-transform: uppercase; font-weight: 600; color: #666; display: block; margin-bottom: 5px; }
        .stat-value { font-size: 1.1rem; font-weight: 700; color: #0f2027; }
        
        .border-expense { border-left-color: #eb4d4b !important; }
        .text-expense { color: #eb4d4b; }

        .search-container { position: relative; margin-top: -25px; z-index: 10; padding: 0 15px; }
        .search-input { border-radius: 30px; padding: 12px 25px; border: none; box-shadow: 0 10px 25px rgba(0,0,0,0.1); width: 100%; max-width: 500px; margin: 0 auto; display: block; text-align: center; }

        .table-container { background: white; border-radius: 20px; overflow: hidden; box-shadow: 0 10px 30px rgba(0,0,0,0.
        
