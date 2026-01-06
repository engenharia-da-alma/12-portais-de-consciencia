@import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap');
/* Custom Scrollbar */
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap');

::-webkit-scrollbar {
  width: 8px;
  height: 8px;
}

::-webkit-scrollbar-track {
  background: rgba(212, 175, 55, 0.1);
  border-radius: 10px;
}

::-webkit-scrollbar-thumb {
  background: rgba(212, 175, 55, 0.5);
  border-radius: 10px;
}

::-webkit-scrollbar-thumb:hover {
  background: rgba(212, 175, 55, 0.7);
}

/* Animations */
@keyframes portalPulse {
  0%, 100% {
    box-shadow: 0 0 0 0 rgba(212, 175, 55, 0.4);
  }
  70% {
    box-shadow: 0 0 0 10px rgba(212, 175, 55, 0);
  }
}

.pulse-portal {
  animation: portalPulse 2s infinite;
}

/* Custom Elements */
.portal-highlight {
  position: relative;
  z-index: 1;
}

.portal-highlight::after {
  content: '';
  position: absolute;
  bottom: 0;
  left: 0;
  width: 100%;
  height: 30%;
  background: rgba(212, 175, 55, 0.3);
  z-index: -1;
  transform: scaleX(0.9);
  transition: all 0.3s ease;
}

.portal-highlight:hover::after {
  height: 40%;
  background: rgba(212, 175, 55, 0.4);
}

/* Portal Grid Animation */
.portal-grid-item {
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.portal-grid-item:hover {
  transform: translateY(-5px);
  box-shadow: 0 10px 20px rgba(0, 0, 0, 0.2);
}
