<template>
    <div class="terms-conditions">
      <h1>Dawn Breeze Limited - Terms and Conditions</h1>
      <p>Last updated: {{ lastUpdated }}</p>
  
      <section>
        <h2>1. Introduction</h2>
        <p>These Terms and Conditions ("Terms") govern your use of Dawn Breeze Limited's website and services. By accessing or using our services, you agree to be bound by these Terms. If you disagree with any part of these Terms, please do not use our services.</p>
      </section>
  
      <section>
        <h2>2. Description of Services</h2>
        <p>Dawn Breeze Limited provides the following services:</p>
        <ul>
          <li><strong>Quote Simulation:</strong> Online calculation and estimation of service costs</li>
          <li><strong>Online Booking:</strong> Ability to schedule and reserve services through our platform</li>
          <li><strong>Customer Account Management:</strong> Personal account creation and management</li>
        </ul>
        <p>While we strive to ensure the accuracy of our quote simulation system, all final prices are subject to confirmation.</p>
      </section>
  
      <section>
        <h2>3. Payment and Cancellation Terms</h2>
        <ul>
          <li><strong>Payment Terms:</strong>
            <ul>
              <li>All prices are displayed in GBP and include applicable VAT</li>
              <li>Payment is required at the time of booking</li>
              <li>We accept major credit cards and bank transfers</li>
            </ul>
          </li>
          <li><strong>Cancellation Policy:</strong>
            <ul>
              <li>Free cancellation up to 48 hours before the scheduled service</li>
              <li>50% charge for cancellations within 24-48 hours of the service</li>
              <li>100% charge for cancellations less than 24 hours before the service</li>
            </ul>
          </li>
        </ul>
      </section>
  
      <section>
        <h2>4. Company Liability</h2>
        <p>Dawn Breeze Limited's liability is defined as follows:</p>
        <ul>
          <li><strong>Service Delays:</strong> We will notify you as soon as possible and offer alternative arrangements.</li>
          <li><strong>Service Unavailability:</strong> We will offer a full refund or reschedule at your convenience.</li>
          <li><strong>Technical Issues:</strong> We will honor any confirmed bookings and prices.</li>
        </ul>
        <p>Our liability is limited to the value of the services booked through our platform.</p>
      </section>
  
      <section>
        <h2>5. Personal Data Protection</h2>
        <p>Your personal data protection is governed by our Privacy Policy, which forms an integral part of these Terms.</p>
      </section>
  
      <section>
        <h2>6. Intellectual Property</h2>
        <p>All content on this website is the property of Dawn Breeze Limited and protected by copyright laws.</p>
      </section>
  
      <section>
        <h2>7. Governing Law</h2>
        <p>These Terms and Conditions are governed by the laws of England and Wales.</p>
      </section>
  
      <section class="important">
        <h2>8. Changes to Terms</h2>
        <p>Dawn Breeze Limited reserves the right to modify these Terms at any time.</p>
      </section>
  
      <section>
        <h2>9. Contact Information</h2>
        <p>For any questions, contact us at:</p>
        <ul>
          <li>Email: legal@dawnbreeze.com</li>
          <li>Address: Dawn Breeze Limited, [Your Address]</li>
          <li>Phone: [Your Phone Number]</li>
        </ul>
      </section>
    </div>
  </template>
  
  <script setup lang="ts">
  import { ref } from 'vue';
  
  const lastUpdated = ref(new Date().toLocaleDateString('en-US'));
  </script>
  
  <style scoped>
  .terms-conditions {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    line-height: 1.6;
    max-width: 800px;
    margin: 0 auto;
    padding: 20px;
    background-color: #fff;
    color: #333;
  }
  
  h1 {
    color: #2c3e50;
    border-bottom: 2px solid #eee;
    padding-bottom: 10px;
  }
  
  h2 {
    color: #34495e;
    margin-top: 30px;
  }
  
  section {
    margin-bottom: 30px;
  }
  
  .important {
    background-color: #f8f9fa;
    padding: 20px;
    border-radius: 5px;
    margin-top: 20px;
  }
  </style>
  