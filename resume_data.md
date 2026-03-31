import profilePicture from '../assets/raffiqProfilePicture.png';

export const resumeData = {
  // Personal Information
  personal: {
    name: "Muhammad Raffiq Zaffri",
    title: "DevOps Engineer | Cloud Optimization | System Infrastructure",
    location: "Malaysia",
    phone: "+60 11-1221 2331",
    email: "raffiq.cloud@example.com",
    github: "github.com/raffiqzaffri",
    linkedin: "linkedin.com/in/raffiqzaffri",
    // avatar: "https://ui-avatars.com/api/?name=Raffiq+Zaffri&size=200&background=2563EB&color=fff&bold=true"
    avatar: profilePicture
  },

  // Professional Summary
  summary: `CompTIA Cloud+ and Meta Back-End certified DevOps Engineer with 2 years of experience managing 16+ production projects. Specialized in Proxmox virtualization, Docker containerization, and full-stack development (FastAPI/React). Proven track record: reduced deployment time by 40%, improved system uptime by 40%, and optimized resource usage by 25%. Expert in Linux administration with 300+ automation scripts and enterprise infrastructure solutions.`,

  // Key Achievements
  achievements: [
    {
      icon: "star",
      title: "Automated Disk Cloning System",
      description: "Deployed Clone Station v2 with 6 parallel stations, reducing cloning time by 60% through FastAPI and WebSocket automation."
    },
    {
      icon: "monitor",
      title: "Enhanced System Monitoring",
      description: "Implemented Zabbix and Netdata across 16+ systems, increasing uptime by 40% with proactive issue detection."
    },
    {
      icon: "heart",
      title: "DevOps Automation Suite",
      description: "Developed 83+ automation scripts for Proxmox, VPN, and monitoring, reducing deployment time by 40%."
    }
  ],

  // Courses & Certifications
  courses: [
    {
      name: "CompTIA Cloud+",
      provider: "CompTIA Certification",
      description: "Cloud infrastructure, virtualization, and security implementation."
    },
    {
      name: "Meta Back-End Developer Professional Certificate",
      provider: "Coursera - Meta Certification",
      description: "Python, Django, REST APIs, database design, and Git."
    },
    {
      name: "Proxmox VE & Virtualization",
      provider: "Production Experience",
      description: "VM/CT management, PCIe passthrough, NVIDIA vGPU configuration."
    }
  ],

  // Languages
  languages: [
    {
      language: "Bahasa Malaysia (Malay)",
      proficiency: "Native"
    },
    {
      language: "English",
      proficiency: "Professional Working Proficiency"
    }
  ],

  // Passions & Interests
  passions: [
    {
      icon: "tech",
      title: "Infrastructure Automation",
      description: "Passionate about advancing infrastructure automation technology to improve system reliability, reduce manual operations, and streamline deployment workflows across diverse environments."
    },
    {
      icon: "monitor",
      title: "System Monitoring & Observability",
      description: "Keen interest in exploring monitoring solutions like Zabbix, Netdata, and custom SMART monitoring systems for proactive issue detection and system health analysis."
    },
    {
      icon: "code",
      title: "Full-Stack Development",
      description: "Active developer building production applications with FastAPI, React, and TypeScript, focusing on real-time WebSocket communication and modern UI/UX design patterns."
    }
  ],

  // Core Skills (Categorized)
  skills: [
    {
      category: "Cloud & Virtualization",
      items: ["Proxmox VE", "Docker", "NVIDIA vGPU", "ZFS + RAID", "NFS Storage", "Virtual Networking"]
    },
    {
      category: "DevOps & Automation",
      items: ["Bash & Python Scripting (300+ scripts)", "Zabbix & Netdata Monitoring", "WireGuard VPN", "CI/CD & Git Workflows", "noVNC Remote Access"]
    },
    {
      category: "Backend Development",
      items: ["Python (FastAPI, Flask)", "Node.js (TypeScript, Express)", "Binary Data Processing", "API Systems", "WebSocket & MQTT"]
    },
    {
      category: "Frontend & UI/UX",
      items: ["React + Vite", "Tailwind CSS v4", "TypeScript", "Responsive Design", "Modern UI Architecture"]
    },
    {
      category: "Specialized Systems",
      items: ["OpenCV (Computer Vision)", "RTSP & WebRTC Streaming", "Edge TTS", "Arduino & IoT", "WordPress Engine Optimization"]
    },
    {
      category: "Soft Skills",
      items: ["Technical Documentation", "Architecture Planning", "Problem Solving", "Rapid Prototyping"]
    }
  ],

  // Professional Experience - Full Time
  fullTimeExperience: [
    {
      title: "System Administrator cum System Developer ",
      company: "Tigaky SDN BHD",
      period: "2023 – December 2025",
      location: "Petaling Jaya, Selangor",
      responsibilities: [
        "Architected enterprise disk cloning platform with 6 parallel stations processing 100+ disks weekly using FastAPI, React+TypeScript, and WebSocket real-time monitoring, reducing manual intervention by 90%",
        "Built comprehensive DevOps automation suite with 83+ production scripts covering Proxmox VE, NVIDIA vGPU, WireGuard VPN, and noVNC remote access, reducing deployment time from hours to minutes",
        "Developed computer vision streaming platform with RTSP-to-WebRTC conversion, PTZ camera control, and Kurento media server serving 10+ simultaneous streams",
        "Implemented infrastructure monitoring with Zabbix and Netdata across 16+ systems with automated alerting and custom dashboards, improving incident response time by 60%"
      ]
    }
  ],

  // Professional Experience - Freelance
  freelanceExperience: [
    {
      title: "Full-Stack Developer / System Administrator",
      company: "Janglapoque Enterprise",
      period: "2024",
      location: "Kuala Lumpur",
      responsibilities: [
        "Managed WordPress deployments for 3+ clients with Apache VirtualHost configurations, MariaDB optimization, and SSL certificates",
        "Automated infrastructure operations with 50+ custom shell scripts for Git workflows, backup systems, and administration tasks"
      ]
    },
    {
      title: "Full-Stack Developer / System Administrator",
      company: "Rantau Digital Enterprise",
      period: "2025",
      location: "Kuala Lumpur",
      responsibilities: [
        "Designed Invoice Generator system with React and TailwindCSS featuring automated generation, client management, and PDF export",
        "Developed custom web applications with Node.js backend and React frontend for enhanced user experience"
      ]
    },
    {
      title: "WordPress Developer / System Administrator",
      company: "Tadika Inovasi Pintar",
      period: "2025",
      location: "Kuala Lumpur",
      responsibilities: [
        "Deployed WordPress website for educational institution using Elementor Pro and Divi Builder with enrollment forms and event calendar",
        "Managed cPanel hosting environment and optimized performance achieving 90+ Google PageSpeed score"
      ]
    }
  ],

  // Key Projects
  projects: [
    {
      name: "Clone Station v2 - Advanced Disk Cloning System",
      description: "Production-grade enterprise disk cloning platform with 6 parallel stations, supporting Windows UEFI/Legacy and Ubuntu image deployment with automated 8-step process from zap to verification.",
      technologies: ["FastAPI", "React", "TypeScript", "Vite", "TailwindCSS", "WebSocket", "Python", "dd", "sgdisk", "parted", "Edge TTS"],
      highlights: [
        "6 concurrent cloning stations with USB port registration and manufacturer detection",
        "Real-time WebSocket monitoring with card-based modern UI",
        "8-step automated process: zap → wipe → partition removal → clone → GPT fix → partprobe → grow/resize → complete",
        "Support for .img files with automatic partition expansion (ntfsresize)",
        "Text-to-speech notifications (Edge TTS with espeak-ng fallback)",
        "REST API endpoints for station control, image management, and status monitoring",
        "Continuous cloning mode with automatic USB detection",
        "Deployed at 192.168.0.249 (hostname: cloneStationv2, user: engineer)"
      ]
    },
    {
      name: "DevOps Infrastructure & Automation Suite",
      description: "Comprehensive collection of 83+ DevOps scripts organized into 7 categories covering Proxmox, virtualization, networking, VPN, monitoring, and specialized setups.",
      technologies: ["Bash", "Python", "Proxmox VE", "Docker", "WireGuard", "OpenWRT", "noVNC", "Zabbix", "Netdata", "NVIDIA vGPU"],
      highlights: [
        "Proxmox host automation: Debian to Proxmox conversion (2 methods), bridge networking, PCIe passthrough, auto-shutdown, Wake-on-LAN",
        "macOS VM setup in Proxmox with proper configuration",
        "WireGuard VPN server/client deployment with multiple configurations",
        "noVNC setup (4 versions) for browser-based remote desktop access",
        "NVIDIA vGPU setup: Proxmox host configuration, license server, guest setup for Debian/Ubuntu/Windows, including crack licensing",
        "OpenWRT router deployment in Proxmox environment",
        "Shinobi NVR installation for Ubuntu surveillance systems",
        "Legacy and UEFI boot configuration scripts with dated versions for rollback"
      ]
    },
    // {
    //   name: "Digital Wedding Invitation Platform (Kad Digital)",
    //   description: "Full-featured wedding invitation website platform with multiple card designs, RSVP management, and guest tracking system.",
    //   technologies: ["LEMP Stack", "Nginx", "PHP-FPM", "MariaDB", "Linux", "Git"],
    //   highlights: [
    //     "Production deployment at getinvitednow.com (192.168.0.223)",
    //     "Multiple customizable card designs in modular subfolder structure",
    //     "MariaDB database (kad_kahwin) with user authentication system",
    //     "Nginx reverse proxy with PHP-FPM processing",
    //     "Git repository: JLRaffiq/Syamimi-Shafiq",
    //     "Custom hostname: digital_kad_kahwin",
    //     "Responsive design for mobile and desktop viewing"
    //   ]
    // },
    {
      name: "Multi-Client WordPress Management & Deployment",
      description: "Enterprise WordPress hosting solution managing 5+ client websites with optimized LAMP stack, automated backups, and security hardening.",
      technologies: ["WordPress", "Apache", "MariaDB", "PHP", "SSL/TLS", "Linux", "cPanel"],
      highlights: [
        "Managed 5+ production WordPress sites for diverse clients (corporate, e-commerce, portfolio)",
        "Custom Apache VirtualHost configurations per client with isolated environments",
        "Database optimization and performance tuning for high-traffic sites",
        "Automated backup solutions with off-site redundancy",
        "SSL certificate management and HTTPS enforcement",
        "WordPress security hardening: file permissions, plugin vetting, malware scanning",
        "Custom theme development and third-party plugin integration",
        "Client training on WordPress administration and content management"
      ]
    },
    {
      name: "SMART Disk Monitoring Systems (Byte Bandit & Original)",
      description: "Dual-system disk health monitoring platform with real-time SMART data analysis, audio notifications, and comprehensive logging.",
      technologies: ["Python", "JavaScript", "React", "Node.js", "PHP", "smartmontools", "HDSentinel"],
      highlights: [
        "Original version: PHP/JavaScript/Node.js/React stack with sound notification system",
        "Byte Bandit v2: Advanced Python/JavaScript/React version with modern frontend",
        "Real-time SMART monitoring dashboard with health status indicators",
        "Automated alerts via audio system (audiovoice/*.wav files)",
        "Comprehensive logging: hdsentinel_log.txt and custom_output.txt",
        "Flowchart documentation (fllowchartDISKStation.jpg/.vsdx)",
        "Support for smartmontools and HDSentinel integration"
      ]
    },
    {
      name: "Vision 2 - Computer Vision & Streaming Platform",
      description: "Advanced computer vision project with RTSP to WebRTC conversion, PTZ camera control, and media streaming infrastructure across multiple iterations.",
      technologies: ["Python", "OpenCV", "Shell Scripts", "RTSP", "WebRTC", "Kurento Media Server", "NFS", "Database"],
      highlights: [
        "313 files covering multiple proof-of-concept implementations",
        "RTSP to WebRTC real-time video conversion",
        "PTZ (Pan-Tilt-Zoom) camera control integration",
        "Multiple versions (v2, v3, v4, v5) with incremental improvements",
        "Kurento media server integration for streaming",
        "NFS setup for shared storage across systems",
        "Comprehensive documentation with images and screenshots",
        "Database integration for camera management and user access"
      ]
    },
    {
      name: "Automated Proxmox Installation Framework",
      description: "Docker-based HTTP delivery system for remote Proxmox VE installation via curl | bash pattern with multiple edition support.",
      technologies: ["Bash", "Docker", "Nginx", "Docker Compose", "Makefile"],
      highlights: [
        "3 editions available: pve8-jedimaster.sh, pve8.sh (standard), pve8-janglapoque.sh",
        "Docker Compose setup with Nginx container serving scripts on port 8080",
        "Remote installation via curl http://server:8080/script.sh | bash",
        "Banner and logo support for branded installations",
        "Makefile for easy management commands (build, start, stop, clean)",
        "Reproducible deployment across multiple servers",
        "Version control for different Proxmox configurations"
      ]
    },
    {
      name: "Invoice Generator System for Rantau Digital",
      description: "Custom invoice generation system for Rantau Digital business operations with modern UI and automated workflow.",
      technologies: ["React", "TailwindCSS", "Node.js", "Linux"],
      highlights: [
        "Deployed at 192.168.0.235 (hostname: invoiceGeneratorRD, user: jedimaster)",
        "6 setup scripts for automated deployment",
        "Tailwind CSS framework for modern, responsive design",
        "Automated invoice generation with customizable templates",
        "Client and project management integration",
        "PDF export functionality for professional invoices"
      ]
    },
    {
      name: "Network Monitoring & Table Hosting System",
      description: "React-based network monitoring dashboard with automated device discovery and management capabilities.",
      technologies: ["React", "Node.js", "nmap", "JavaScript"],
      highlights: [
        "Automated network scanning with nmap integration",
        "Real-time network device discovery and tracking",
        "Network data table hosting and visualization",
        "Results logging in nmap.txt for historical tracking",
        "Device status monitoring and alerts",
        "Support for custom network ranges and scanning profiles"
      ]
    }
  ],

  // Technical Stack
  technologies: [
    "Linux (Debian/Ubuntu)",
    "Python (FastAPI, Flask)",
    "JavaScript/TypeScript",
    "Bash/Shell Scripting",
    "React + Vite",
    "TailwindCSS",
    "Node.js + Express",
    "PHP + PHP-FPM",
    "FastAPI + WebSocket",
    "Docker + Docker Compose",
    "Proxmox VE",
    "MariaDB/MySQL",
    "Nginx + Apache",
    "Git (Multi-account)",
    "WordPress",
    "OpenCV",
    "RTSP/WebRTC",
    "WireGuard VPN",
    "OpenWrt",
    "smartmontools",
    "HDSentinel",
    "ZFS + RAID",
    "Zabbix + Netdata",
    "noVNC",
    "Kurento Media Server",
    "Arduino (WiFiNINA)",
    "MQTT (PubSubClient)",
    "Edge TTS",
    "NVIDIA vGPU",
    "NFS Storage"
  ],

  // Education
  education: [
    {
      degree: "Foundation in Business And Law",
      institution: "Yayasan Peneraju Cheras (YPC)",
      period: "2021",
      location: "Malaysia"
    },
    {
      degree: "Bachelor of Multimedia Computing (Hons)",
      institution: "Yayasan Peneraju Cheras (YPC)",
      period: "2021 - 2023",
      location: "Malaysia"
    }
  ],

  // Additional Information
  additional: [
    "Portfolio of 16+ active production projects combining hardware, software, and automation",
    "300+ shell scripts and 90+ Python files demonstrating strong automation expertise",
    "Proven ability to deliver production-ready systems with comprehensive monitoring and logging"
  ],

  // Professional References
  references: [
    {
      name: "Norsyamimi binti Abdul Hamid",
      title: "HR Manager",
      company: "Tigaky SDN BHD",
      project: "Clone Station v2 & Infrastructure Projects",
      email: "syamimi@tigaky.com",
      phone: "+60 12-XXX XXXX"
    },
    {
      name: "Najwan",
      title: "Project Coordinator",
      company: "JangLapoque Enterprise",
      project: "Digital Wedding Invitation Platform",
      email: "najwan@janglapoque.com",
      phone: "+60 13-XXX XXXX"
    }
  ],

  // Volunteer & Community
  volunteer: [
    {
      role: "Technical Mentor",
      organization: "Medical Awareness Camp Outreach Community",
      description: "Provided technical guidance and support for students and junior developers, focusing on Linux system administration, DevOps practices, and automation workflows."
    }
  ]
};
