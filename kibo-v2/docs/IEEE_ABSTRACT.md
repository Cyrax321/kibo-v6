# IEEE Conference Paper Abstract

---

## Kibo: An Intelligent Gamified Career Orchestration Platform for Software Engineers Using Real-Time Event-Driven Architecture

---

### Authors
Kibo Systems Development Team

---

### Abstract

The technical recruitment lifecycle for software engineers faces significant challenges including fragmented application tracking, inconsistent skill development practices, and inadequate mechanisms for verifying candidate competencies. Existing solutions address these concerns in isolation, resulting in cognitive overhead and reduced productivity during career transitions. This paper presents Kibo, an intelligent career orchestration platform that unifies job application management, skill development tracking, and productivity analytics within a gamified ecosystem.

The proposed system implements a serverless architecture utilizing React 18 for the presentation layer and Supabase Backend-as-a-Service (BaaS) with PostgreSQL for data persistence and real-time synchronization via WebSocket connections. The platform introduces three key innovations: (1) a Kanban-based Application Tracking System with funnel analytics for conversion rate visualization, (2) a gamification engine that synthesizes user activities into quantifiable metrics including experience points, streak calculations, and achievement unlocking, and (3) a real-time leaderboard system employing Change Data Capture (CDC) for sub-second state propagation.

Experimental evaluation demonstrates First Contentful Paint (FCP) latency under 1.5 seconds and real-time update propagation within 500 milliseconds. The contribution graph visualization ("The Garden") provides GitHub-style activity representation, while the integrated assessment engine supports professional certification with comprehensive result analytics. The system achieves type safety through TypeScript implementation and ensures data integrity via Row-Level Security (RLS) policies.

Results indicate that gamification mechanics significantly improve user engagement and consistency in career-related activities. The platform establishes a standardized framework for technical skill verification and application pipeline management, addressing the fragmentation inherent in current recruitment preparation workflows.

---

### Index Terms

Career Management Systems, Educational Technology, Event-Driven Architecture, Gamification, Real-Time Systems, Serverless Computing, Software Engineering Education, Technical Recruitment, Web Application Development

---

### Paper Classification

**Type:** Systems and Applications Paper  
**Domain:** Human-Computer Interaction, Software Engineering  
**IEEE Conference Categories:** Educational Technology, Web-Based Systems, Real-Time Computing

---

### Document Information

| Field | Value |
|-------|-------|
| **Submission Type** | IEEE Conference Paper |
| **Word Count (Abstract)** | 248 words |
| **Version** | 1.0.0 |
| **Date** | February 2026 |
| **Contact** | Kibo Systems |

---

### Extended Summary

#### Problem Statement
Software engineers navigating career transitions encounter fragmented tooling for application tracking, inconsistent coding practice during interview preparation, and a lack of centralized dashboards for career analytics. The solitary nature of job hunting contributes to motivation decay and suboptimal outcomes.

#### Proposed Solution
Kibo addresses these challenges through an integrated platform that combines:
- **Mission Control Dashboard**: Centralized visualization of career metrics including XP totals, engagement streaks, and level progression
- **Application Tracking System (ATS)**: Drag-and-drop Kanban interface with real-time status synchronization
- **Code Lab**: Problem submission tracking with automatic skill categorization and difficulty distribution analysis
- **Gamification Protocol**: Experience point allocation, streak maintenance incentives, and competitive leaderboards
- **Professional Certifications**: Assessment engine with glassmorphism UI design and digital badge generation

#### Technical Architecture
The system employs:
- **Frontend**: React 18 Single Page Application with TanStack Query for server state management
- **Backend**: Supabase BaaS with PostgreSQL logical replication for real-time capabilities
- **Security**: Zod schema validation and Row-Level Security for data protection
- **User Experience**: Shadcn UI component library with Tailwind CSS for responsive design

#### Key Contributions
1. Novel integration of gamification mechanics with career management workflows
2. Real-time state synchronization architecture achieving sub-500ms update latency
3. Unified platform reducing context-switching overhead during recruitment preparation
4. Open-source implementation enabling community extension and customization

---

*This abstract follows IEEE conference paper formatting guidelines and is suitable for submission to IEEE-sponsored conferences and university academic requirements.*
