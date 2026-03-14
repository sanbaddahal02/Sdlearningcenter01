# Sdlearningcenter01
SD learning center is an online learning platform for class 9 to 12 students. we offer high quality Accounts and Economics classes designed for +2 management students. Join for first month only rs 500!! hurryup sign in for now here i am a BBA student and i can teach you in a easy way
<section class="admission-section" id="admission">
    <div class="admission-container">
        <h2 style="text-align: center; margin-bottom: 30px; font-size: 2.5rem; color: #fff;">Student Admission</h2>
        <p style="text-align: center; margin-bottom: 40px; opacity: 0.7;">Enroll now for Class 9–12 Coaching in Accounts & Economics</p>
        
        <form action="https://formspree.io/f/your_formspree_id_here" method="POST" class="admission-form">
            <div class="form-grid">
                <div class="input-group">
                    <label>Student Full Name</label>
                    <input type="text" name="student_name" placeholder="Enter name" required>
                </div>
                <div class="input-group">
                    <label>Current Address</label>
                    <input type="text" name="address" placeholder="e.g. Dharan 17" required>
                </div>
                <div class="input-group">
                    <label>Age</label>
                    <input type="number" name="age" placeholder="Age" required>
                </div>
                <div class="input-group">
                    <label>Phone Number</label>
                    <input type="tel" name="phone" placeholder="98XXXXXXXX" required>
                </div>
                <div class="input-group">
                    <label>School/College Name</label>
                    <input type="text" name="institution" placeholder="Enter school name" required>
                </div>
                <div class="input-group">
                    <label>Class Level</label>
                    <select name="class_level" required>
                        <option value="" disabled selected>Select Class</option>
                        <option value="9">Class 9</option>
                        <option value="10">Class 10</option>
                        <option value="11">Class 11</option>
                        <option value="12">Class 12</option>
                    </select>
                </div>
            </div>
            <button type="submit" class="submit-btn">Submit Application</button>
        </form>
    </div>
</section>

<style>
    .admission-section { padding: 80px 8%; background: #0f172a; }
    .admission-container { 
        max-width: 800px; 
        margin: 0 auto; 
        background: rgba(255,255,255,0.03); 
        padding: 50px; 
        border-radius: 30px; 
        border: 1px solid rgba(255,255,255,0.1);
        box-shadow: 0 20px 40px rgba(0,0,0,0.3);
    }
    .form-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 20px; }
    .input-group { display: flex; flex-direction: column; gap: 8px; margin-bottom: 15px; }
    .input-group label { font-size: 0.9rem; font-weight: 600; color: #3b82f6; }
    .input-group input, .input-group select {
        padding: 12px;
        background: rgba(255,255,255,0.05);
        border: 1px solid rgba(255,255,255,0.2);
        border-radius: 10px;
        color: #fff;
        outline: none;
        transition: 0.3s;
    }
    .input-group input:focus { border-color: #3b82f6; background: rgba(255,255,255,0.1); }
    .submit-btn {
        width: 100%;
        padding: 15px;
        margin-top: 20px;
        background: #3b82f6;
        color: #fff;
        border: none;
        border-radius: 12px;
        font-weight: bold;
        font-size: 1.1rem;
        cursor: pointer;
        transition: 0.3s;
    }
    .submit-btn:hover { background: #2563eb; transform: translateY(-3px); box-shadow: 0 10px 20px rgba(59, 130, 246, 0.3); }
</style>
