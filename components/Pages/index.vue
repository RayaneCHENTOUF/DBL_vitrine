<template>
  <div class="page-wrapper">
    <!-- Header -->
    <header class="header">
      <div class="container">
        <div class="header-content">
          <div class="logo-section">
            <div class="logo-icon">
              <svg class="icon" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 7v10a2 2 0 002 2h14a2 2 0 002-2V9a2 2 0 00-2-2H5a2 2 0 00-2-2z"></path>
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8 7V5a2 2 0 012-2h4a2 2 0 012 2v2m-6 4h4"></path>
              </svg>
            </div>
            <h1 class="company-name">{{ companyInfo.name }}</h1>
          </div>
          <div class="coming-soon-badge">
            Coming Soon
          </div>
        </div>
      </div>
    </header>

    <!-- Hero Section -->
    <section class="hero-section">
      <div class="container">
        <div class="hero-content">
          <div class="hero-text">
            <h2 class="hero-title">
              Your Trusted <span class="text-accent">Moving Partner</span>
            </h2>
            <p class="hero-description">
              Professional moving services across England. We're preparing to launch our comprehensive 
              relocation solutions to make your next move stress-free and seamless.
            </p>
            <div class="launch-card">
              <div class="launch-icon-wrapper">
                <div class="launch-icon">
                  <svg class="icon-large" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z"></path>
                  </svg>
                </div>
              </div>
              <h3 class="launch-title">Launching Soon</h3>
              <p class="launch-text">
                We're putting the finishing touches on our services. Stay tuned for the official launch!
              </p>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Company Information -->
    <section class="company-section">
      <div class="container">
        <div class="section-header">
          <h2 class="section-title">About {{ companyInfo.name }}</h2>
          <div class="section-divider"></div>
        </div>
        
        <div class="company-grid">
          <div class="company-info">
            <h3 class="info-title">Who We Are</h3>
            <p class="info-description">
              {{ companyInfo.description }}
            </p>
            <div class="features-list">
              <div class="feature-item">
                <div class="feature-icon">
                  <svg class="icon-small" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path>
                  </svg>
                </div>
                <span class="feature-text">Professional and reliable service</span>
              </div>
              <div class="feature-item">
                <div class="feature-icon">
                  <svg class="icon-small" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path>
                  </svg>
                </div>
                <span class="feature-text">Fully insured and licensed</span>
              </div>
              <div class="feature-item">
                <div class="feature-icon">
                  <svg class="icon-small" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path>
                  </svg>
                </div>
                <span class="feature-text">Competitive pricing</span>
              </div>
            </div>
          </div>
          
          <div class="contact-card">
            <h3 class="contact-title">Contact Information</h3>
            <div class="contact-list">
              <div class="contact-item">
                <div class="contact-icon">
                  <svg class="icon-medium" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z"></path>
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z"></path>
                  </svg>
                </div>
                <div class="contact-info">
                  <p class="contact-label">Location</p>
                  <p class="contact-value">{{ companyInfo.location }}</p>
                </div>
              </div>
              
              <div class="contact-item">
                <div class="contact-icon">
                  <svg class="icon-medium" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"></path>
                  </svg>
                </div>
                <div class="contact-info">
                  <p class="contact-label">Phone</p>
                  <p class="contact-value">{{ companyInfo.phone }}</p>
                </div>
              </div>
              
              <div class="contact-item">
                <div class="contact-icon">
                  <svg class="icon-medium" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"></path>
                  </svg>
                </div>
                <div class="contact-info">
                  <p class="contact-label">Email</p>
                  <p class="contact-value">{{ companyInfo.email }}</p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Future Projects -->
    <section class="projects-section">
      <div class="container">
        <div class="section-header">
          <h2 class="section-title">Our Upcoming Services</h2>
          <div class="section-divider"></div>
          <p class="section-description">
            We're developing comprehensive moving solutions to serve you better. Here's what's coming soon.
          </p>
        </div>
        
        <div class="projects-grid">
          <div v-for="project in futureProjects" :key="project.id" class="project-card">
            <div class="project-content">
              <div class="project-icon-wrapper">
                <div class="project-icon">
                  <svg class="icon" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" :d="project.icon"></path>
                  </svg>
                </div>
              </div>
              <h3 class="project-title">{{ project.title }}</h3>
              <p class="project-description">{{ project.description }}</p>
              <div class="project-footer">
                <span class="project-status">{{ project.status }}</span>
                <span class="project-timeline">{{ project.timeline }}</span>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>


    <!-- Footer -->
    <footer class="footer">
      <div class="container">
        <div class="footer-grid">
          <div class="footer-brand">
            <h3 class="footer-title">{{ companyInfo.name }}</h3>
            <p class="footer-description">
              Your trusted moving partner in England. Professional, reliable, and coming soon.
            </p>
          </div>
          
          <div class="footer-links">
            <h4 class="footer-heading">Quick Links</h4>
            <ul class="links-list">
              <li><NuxtLink to="/privacy-policy">Privacy Policy</NuxtLink></li>
              <li><NuxtLink to="/terms-conditions">Terms & Conditions</NuxtLink></li>
            </ul>
          </div>
          
          <div class="footer-social">
            <h4 class="footer-heading">Connect With Us</h4>
            <div class="social-links">
              <a href="#" class="social-link">
                <svg class="social-icon" fill="currentColor" viewBox="0 0 24 24">
                  <path d="M24 4.557c-.883.392-1.832.656-2.828.775 1.017-.609 1.798-1.574 2.165-2.724-.951.564-2.005.974-3.127 1.195-.897-.957-2.178-1.555-3.594-1.555-3.179 0-5.515 2.966-4.797 6.045-4.091-.205-7.719-2.165-10.148-5.144-1.29 2.213-.669 5.108 1.523 6.574-.806-.026-1.566-.247-2.229-.616-.054 2.281 1.581 4.415 3.949 4.89-.693.188-1.452.232-2.224.084.626 1.956 2.444 3.379 4.6 3.419-2.07 1.623-4.678 2.348-7.29 2.04 2.179 1.397 4.768 2.212 7.548 2.212 9.142 0 14.307-7.721 13.995-14.646.962-.695 1.797-1.562 2.457-2.549z"/>
                </svg>
              </a>
              <a href="#" class="social-link">
                <svg class="social-icon" fill="currentColor" viewBox="0 0 24 24">
                  <path d="M22.46 6c-.77.35-1.6.58-2.46.69.88-.53 1.56-1.37 1.88-2.38-.83.5-1.75.85-2.72 1.05C18.37 4.5 17.26 4 16 4c-2.35 0-4.27 1.92-4.27 4.29 0 .34.04.67.11.98C8.28 9.09 5.11 7.38 3 4.79c-.37.63-.58 1.37-.58 2.15 0 1.49.75 2.81 1.91 3.56-.71 0-1.37-.2-1.95-.5v.03c0 2.08 1.48 3.82 3.44 4.21a4.22 4.22 0 0 1-1.93.07 4.28 4.28 0 0 0 4 2.98 8.521 8.521 0 0 1-5.33 1.84c-.34 0-.68-.02-1.02-.06C3.44 20.29 5.7 21 8.12 21 16 21 20.33 14.46 20.33 8.79c0-.19 0-.37-.01-.56.84-.6 1.56-1.36 2.14-2.23z"/>
                </svg>
              </a>
              <a href="#" class="social-link">
                <svg class="social-icon" fill="currentColor" viewBox="0 0 24 24">
                  <path d="M20.447 20.452h-3.554v-5.569c0-1.328-.027-3.037-1.852-3.037-1.853 0-2.136 1.445-2.136 2.939v5.667H9.351V9h3.414v1.561h.046c.477-.9 1.637-1.85 3.37-1.85 3.601 0 4.267 2.37 4.267 5.455v6.286zM5.337 7.433c-1.144 0-2.063-.926-2.063-2.065 0-1.138.92-2.063 2.063-2.063 1.14 0 2.064.925 2.064 2.063 0 1.139-.925 2.065-2.064 2.065zm1.782 13.019H3.555V9h3.564v11.452zM22.225 0H1.771C.792 0 0 .774 0 1.729v20.542C0 23.227.792 24 1.771 24h20.451C23.2 24 24 23.227 24 22.271V1.729C24 .774 23.2 0 22.222 0h.003z"/>
                </svg>
              </a>
            </div>
          </div>
        </div>
        
        <div class="footer-bottom">
          <p class="copyright">&copy; 2025 {{ companyInfo.name }}. All rights reserved.</p>
        </div>
      </div>
    </footer>
  </div>
</template>

<script setup>
// Meta tags for SEO
useHead({
  title: 'DAWN-BREEZE-LTD - Professional Moving Services in England',
  meta: [
    { name: 'description', content: 'Professional moving services across England. Coming soon - your trusted partner for stress-free relocations.' },
    { name: 'keywords', content: 'moving services, relocation, England, professional movers, house moving' }
  ]
})

// Company information
const companyInfo = {
  name: 'DAWN-BREEZE-LIMITED',
  description: 'DAWN-BREEZE-LTD is a premier moving company dedicated to providing exceptional relocation services across England. With years of experience in the industry, we understand that moving can be one of life\'s most stressful experiences. That\'s why we\'re committed to making your transition as smooth and hassle-free as possible.',
  location: 'London, England',
  phone: '+44 20 7946 0958',
  email: 'DawnBreezeLimited@gmail.com'
}

// Future projects/services
const futureProjects = [
  {
    id: 1,
    title: 'Residential Moving',
    description: 'Complete home relocation services for families and individuals. From packing to unpacking, we handle it all.',
    status: 'In Development',
    timeline: 'Q3 2025',
    icon: 'M3 7v10a2 2 0 002 2h14a2 2 0 002-2V9a2 2 0 00-2-2H5a2 2 0 00-2-2z'
  },
  {
    id: 2,
    title: 'Commercial Moving',
    description: 'Professional office and business relocations with minimal downtime. Specialized equipment and expert handling.',
    status: 'Planning Phase',
    timeline: 'Q4 2025',
    icon: 'M19 21V5a2 2 0 00-2-2H7a2 2 0 00-2 2v16m14 0h2m-2 0h-5m-9 0H3m2 0h5M9 7h1m-1 4h1m4-4h1m-1 4h1m-5 10v-5a1 1 0 011-1h2a1 1 0 011 1v5m-4 0h4'
  },
]
</script>

<style scoped>
/* Reset et styles de base */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
  line-height: 1.6;
  color: #374151;
}

/* Conteneur principal */
.page-wrapper {
  min-height: 100vh;
  background: linear-gradient(to bottom right, #f0fdf4, #f9fafb);
}

.container {
  max-width: 1200px;
  margin: 0 auto;
  padding: 0 1.5rem;
}

/* Header */
.header {
  background-color: #ffffff;
  box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.1), 0 4px 6px -2px rgba(0, 0, 0, 0.05);
}

.header-content {
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 1rem 0;
}

.logo-section {
  display: flex;
  align-items: center;
  gap: 0.75rem;
}

.logo-icon {
  width: 2.5rem;
  height: 2.5rem;
  background-color: #16a34a;
  border-radius: 0.5rem;
  display: flex;
  align-items: center;
  justify-content: center;
}

.icon {
  width: 1.5rem;
  height: 1.5rem;
  color: #ffffff;
}

.company-name {
  font-size: 1.5rem;
  font-weight: 700;
  color: #1f2937;
}

.coming-soon-badge {
  background-color: #dcfce7;
  color: #166534;
  padding: 0.5rem 1rem;
  border-radius: 9999px;
  font-size: 0.875rem;
  font-weight: 600;
}

/* Section Hero */
.hero-section {
  position: relative;
  padding: 5rem 1.5rem;
  background: linear-gradient(135deg, #f0fdf4 0%, #ffffff 100%);
}

.hero-content {
  text-align: center;
}

.hero-text {
  max-width: 56rem;
  margin: 0 auto;
  animation: fadeInUp 0.6s ease-out;
}

.hero-title {
  font-size: 3rem;
  font-weight: 700;
  color: #1f2937;
  margin-bottom: 1.5rem;
}

.text-accent {
  color: #16a34a;
}

.hero-description {
  font-size: 1.25rem;
  color: #4b5563;
  margin-bottom: 2rem;
  line-height: 1.625;
}

.launch-card {
  background-color: #ffffff;
  border-radius: 0.5rem;
  box-shadow: 0 20px 25px -5px rgba(0, 0, 0, 0.1), 0 10px 10px -5px rgba(0, 0, 0, 0.04);
  padding: 2rem;
  max-width: 42rem;
  margin: 0 auto;
  transition: all 0.3s ease;
}

.launch-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 25px 50px -12px rgba(0, 0, 0, 0.25);
}

.launch-icon-wrapper {
  display: flex;
  align-items: center;
  justify-content: center;
  margin-bottom: 1rem;
}

.launch-icon {
  width: 4rem;
  height: 4rem;
  background-color: #dcfce7;
  border-radius: 9999px;
  display: flex;
  align-items: center;
  justify-content: center;
}

.icon-large {
  width: 2rem;
  height: 2rem;
  color: #16a34a;
}

.launch-title {
  font-size: 1.5rem;
  font-weight: 700;
  color: #1f2937;
  margin-bottom: 0.5rem;
}

.launch-text {
  color: #4b5563;
}

/* Section entreprise */
.company-section {
  padding: 4rem 0;
  background-color: #ffffff;
}

.section-header {
  text-align: center;
  margin-bottom: 3rem;
}

.section-title {
  font-size: 1.875rem;
  font-weight: 700;
  color: #1f2937;
  margin-bottom: 1rem;
}

.section-divider {
  width: 6rem;
  height: 0.25rem;
  background-color: #16a34a;
  margin: 0 auto;
}

.company-grid {
  display: grid;
  grid-template-columns: 1fr;
  gap: 3rem;
  align-items: center;
}

@media (min-width: 768px) {
  .company-grid {
    grid-template-columns: repeat(2, 1fr);
  }
}

.info-title {
  font-size: 1.5rem;
  font-weight: 600;
  color: #1f2937;
  margin-bottom: 1rem;
}

.info-description {
  color: #4b5563;
  margin-bottom: 1.5rem;
  line-height: 1.625;
}

.features-list {
  display: flex;
  flex-direction: column;
  gap: 1rem;
}

.feature-item {
  display: flex;
  align-items: center;
  gap: 0.75rem;
}

.feature-icon {
  width: 2rem;
  height: 2rem;
  background-color: #dcfce7;
  border-radius: 9999px;
  display: flex;
  align-items: center;
  justify-content: center;
}

.icon-small {
  width: 1rem;
  height: 1rem;
  color: #16a34a;
}

.feature-text {
  color: #374151;
}

.contact-card {
  background-color: #f9fafb;
  border-radius: 0.5rem;
  padding: 2rem;
}

.contact-title {
  font-size: 1.5rem;
  font-weight: 600;
  color: #1f2937;
  margin-bottom: 1.5rem;
}

.contact-list {
  display: flex;
  flex-direction: column;
  gap: 1rem;
}

.contact-item {
  display: flex;
  align-items: center;
  gap: 1rem;
}

.contact-icon {
  width: 2.5rem;
  height: 2.5rem;
  background-color: #16a34a;
  border-radius: 0.5rem;
  display: flex;
  align-items: center;
  justify-content: center;
}

.icon-medium {
  width: 1.25rem;
  height: 1.25rem;
  color: #ffffff;
}

.contact-label {
  font-weight: 600;
  color: #1f2937;
}

.contact-value {
  color: #4b5563;
}

/* Section projets */
.projects-section {
  padding: 4rem 0;
  background-color: #f9fafb;
}

.section-description {
  color: #4b5563;
  max-width: 42rem;
  margin: 1rem auto 0;
}

.projects-grid {
  display: grid;
  grid-template-columns: 1fr;
  gap: 2rem;
}

@media (min-width: 768px) {
  .projects-grid {
    grid-template-columns: repeat(3, 1fr);
  }
}

.project-card {
  background-color: #ffffff;
  border-radius: 0.5rem;
  box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.1), 0 4px 6px -2px rgba(0, 0, 0, 0.05);
  overflow: hidden;
  transition: all 0.3s ease;
}

.project-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 25px 50px -12px rgba(0, 0, 0, 0.25);
}

.project-content {
  padding: 1.5rem;
}

.project-icon-wrapper {
  margin-bottom: 1rem;
}

.project-icon {
  width: 3rem;
  height: 3rem;
  background-color: #dcfce7;
  border-radius: 0.5rem;
  display: flex;
  align-items: center;
  justify-content: center;
}

.project-title {
  font-size: 1.25rem;
  font-weight: 600;
  color: #1f2937;
  margin-bottom: 0.75rem;
}

.project-description {
  color: #4b5563;
  margin-bottom: 1rem;
}

.project-footer {
  display: flex;
  align-items: center;
  justify-content: space-between;
}

.project-status {
  font-size: 0.875rem;
  color: #16a34a;
  font-weight: 600;
}

.project-timeline {
  font-size: 0.875rem;
  color: #6b7280;
}
/* Footer */
.footer {
  background-color: #1f2937;
  color: #ffffff;
  padding: 3rem 0;
}

.footer-grid {
  display: grid;
  grid-template-columns: 1fr;
  gap: 2rem;
}

@media (min-width: 768px) {
  .footer-grid {
    grid-template-columns: repeat(3, 1fr);
  }
}

.footer-title {
  font-size: 1.25rem;
}
.footer-description {
  margin-top: 0.5rem;
  color: #d1d5db;
}
.footer-links {
  margin-top: 1.5rem;
}
.footer-heading {
  font-size: 1rem;
  font-weight: 600;
  color: #ffffff;
  margin-bottom: 0.75rem;
}
.links-list {
  list-style: none;
  padding: 0;
}
.links-list li {
  margin-bottom: 0.5rem;
}
.footer-link {
  color: #d1d5db;
  text-decoration: none;
  transition: color 0.3s ease;
}
.footer-link:hover {
  color: #ffffff;
}
.footer-social {
  margin-top: 1.5rem;
}
.social-links {
  display: flex;
  gap: 1rem;
}
.social-link {
  color: #d1d5db;
  transition: color 0.3s ease;
}
.social-link:hover {
  color: #ffffff;
}
.social-icon {
  width: 1.5rem;
  height: 1.5rem;
}
.footer-bottom {
  margin-top: 2rem;
  text-align: center;
  color: #d1d5db;
}
</style>