+++
title = "Connect With Us"
meta_title = "Send Us Your Inquiry"
description = "Use this form to connect with us and submit your questions or requests."
date = 2025-06-20T10:15:00+05:30
draft = false
+++
Connect With Us
We’d love to hear from you! Please fill out the form below to connect with the relevant team.
<form name="contact" method="POST" data-netlify="true" netlify-honeypot="bot-field" action="/thank-you/">
    <p class="hidden">
        <label>Don’t fill this out if you’re human: <input name="bot-field" /></label>
    </p>
    <div class="form-group">
        <label for="inquiryType">Your Inquiry Type:</label>
        <select id="inquiryType" name="inquiryType" required>
            <option value="">-- Please choose an option --</option>
            <option value="industry-msme-startup">Industry / MSME / Startup Collaboration</option>
            <option value="academia-research">Academia / Research Collaboration</option>
            <option value="general-inquiry">General Inquiry</option>
            <option value="other">Other</option>
        </select>
    </div>
    <div class="form-group">
        <label for="requesterName">Your Name:</label>
        <input type="text" id="requesterName" name="requesterName" required>
    </div>
    <div class="form-group">
        <label for="requesterDesignation">Your Designation:</label>
        <input type="text" id="requesterDesignation" name="requesterDesignation">
    </div>
    <div class="form-group">
        <label for="requesterDivision">Your Organization / Division:</label>
        <input type="text" id="requesterDivision" name="requesterDivision">
    </div>
    <div class="form-group">
        <label for="requesterEmail">Your Email ID:</label>
        <input type="email" id="requesterEmail" name="requesterEmail" required>
    <div class="form-group">
        <label for="contactPerson">Who would you like to contact?:</label>
        <input type="text" id="contactPerson" name="contactPerson">
    </div>
    <div class="form-group">
        <label for="message">What would you like to ask? (Max 500 characters):</label>
        <textarea id="message" name="message" rows="5" maxlength="500" required></textarea>
    </div>
    <div class="form-group">
        <button type="submit">Send Message</button>
    </div>
    <p>
    </p>
</form>

<style>
    /* Basic inline styling for demonstration. You should ideally put this in your theme's CSS */
    .form-group {
        margin-bottom: 15px;
    }
    .form-group label {
        display: block;
        margin-bottom: 5px;
        font-weight: bold;
    }
    .form-group input[type="text"],
    .form-group input[type="email"],
    .form-group select,
    .form-group textarea {
        width: 100%;
        padding: 8px;
        border: 1px solid #ddd;
        border-radius: 4px;
        box-sizing: border-box; /* Ensures padding doesn't increase width */
    }
    .form-group textarea {
        resize: vertical; /* Allow vertical resizing */
    }
    .form-group button {
        background-color: #007bff;
        color: white;
        padding: 10px 15px;
        border: none;
        border-radius: 4px;
        cursor: pointer;
        font-size: 16px;
    }
    .form-group button:hover {
        background-color: #0056b3;
    }
    .hidden {
        display: none;
    }
</style>