# NetKofi – Third-Space Networking Platform

NetKofi is a third-space inspired professional networking platform designed to transform
short networking encounters into long-term professional relationships.

Unlike traditional networking platforms that prioritize the number of connections,
NetKofi focuses on meaningful interactions, real-world meetups, and sustained engagement
between students and professionals.

The platform combines digital networking tools with activity-based interaction systems
to encourage authentic connections rather than passive contact lists.


------------------------------------------------------------
PROBLEM
------------------------------------------------------------

Modern networking environments emphasize quantity over quality.
Students and young professionals attend events or connect online,
but these interactions rarely develop into mentorships,
collaborations, or lasting professional relationships.

Key issues include:

- Surface-level networking
- Lack of structured follow-up
- Passive connection lists with minimal engagement
- Difficulty maintaining connections after events

NetKofi addresses this by creating an interaction-driven networking ecosystem
that promotes accountability and continued engagement.


------------------------------------------------------------
KEY FEATURES
------------------------------------------------------------

Network Graph Visualization
- Interactive professional network graph
- Displays first and second degree connections
- Shows shared events and activities
- Built using D3.js

Interaction Rating System
- Users rate interaction quality after events
- Encourages accountability in networking
- Promotes follow-up interactions

Activity Status System
- Users share real-time activity updates
- Example: studying at a cafe, working on a project
- Connections can join shared activities

Time Slot Booking
- Structured networking sessions
- Schedule coffee chats or collaborations
- Reduces scheduling friction

Meetup Tracking
- Tracks attended events and activities
- Connections only created after shared interaction
- Prevents random follower networks


------------------------------------------------------------
TECH STACK
------------------------------------------------------------

Frontend
- React
- Vite
- JavaScript (ES6+)
- HTML5
- CSS3
- D3.js

Backend
- Supabase JS Client

Database
- Supabase PostgreSQL

Authentication
- Supabase Authentication
- Email login
- Google login
- LinkedIn login

Developer Tools
- npm
- ESLint
- Hot Module Replacement (HMR)


------------------------------------------------------------
SYSTEM ARCHITECTURE
------------------------------------------------------------

Frontend (React + Vite)
        |
        v
Supabase JS Client (API Layer)
        |
        v
Supabase Database + Authentication
        |
        v
User Profiles | Network Graph | Interaction Logs


------------------------------------------------------------
HOW IT WORKS
------------------------------------------------------------

1. Users create accounts through Supabase authentication.
2. User profiles are stored in the Supabase database.
3. Connections are created after shared events or activities.
4. Interaction ratings and activity statuses update the network graph.
5. Users schedule meetups through time-slot booking.


------------------------------------------------------------
TESTING
------------------------------------------------------------

The prototype was tested for:

- Functional feature behavior
- Dynamic UI updates
- Network graph accuracy
- Activity status visibility
- Responsive interface across screen sizes

Simulated user interactions confirmed that the platform
correctly demonstrates relationship tracking and engagement.


------------------------------------------------------------
IMPACT
------------------------------------------------------------

NetKofi transforms networking from a static contact list
into a dynamic relationship ecosystem.

Expected benefits include:

- Stronger professional relationships
- Increased engagement after networking events
- Improved mentorship opportunities
- More collaborative interactions


------------------------------------------------------------
FUTURE IMPROVEMENTS
------------------------------------------------------------

Potential future developments:

- Mobile application support
- AI networking recommendations
- Calendar integrations
- Event recommendation systems
- Network analytics dashboards
