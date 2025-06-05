# Privacy Policy

**Effective Date:** 5 Jun 2025

This Privacy Policy explains how we collect, use, and protect your data when using our Discord bot ("EvoBot"). By using EvoBot, you agree to the terms outlined below.

## 1. Data We Collect

We collect and store the following types of data to provide our services:

### 1.1 Server and Channel Identifiers
- `guildId` (Server ID)
- `channelId` (Channel ID)
- `messageId` (Message ID)
- `shardId` (Bot shard identifier)

### 1.2 User Identifiers and Data
- `userId` (User Discord ID)
- `hostedBy` (Giveaway host user ID)
- `participants` (List of participant user IDs)
- User avatar URLs (for effect command processing)

### 1.3 Giveaway System Data
- Giveaway emoji and emoji ID
- Prize name and description
- Number of winners
- End time/timestamp
- Participant lists
- Custom messages for guild-specific participation requirements
- Target guild settings for cross-server giveaways

### 1.4 Welcome and Greeting System Data
- Welcome messages and custom text
- Message deletion timers (`delafter`)
- Channel-specific greeting configurations
- Welcome card customization settings:
  - Text and name colors
  - Move and zoom values for visual effects
  - Welcome card enable/disable states
- Greeting system enable/disable states per channel

### 1.5 User Personal Preferences
- `hideMeToggle`: Whether your platform activity is visible to others

### 1.6 Server Activity Tracking and Analytics
#### Online Member Statistics
- Online member counts with timestamps
- Total member counts and percentages
- Hourly and daily activity patterns
- Peak online times and dates
- Weekly and monthly averages

#### Gaming Activity Data
- Total gaming member counts
- Top games being played with player counts
- Game session durations
- Gaming activity trends and peaks
- Individual game details and statistics

#### Mention Impact Analysis
- Member count before and after @everyone
- Mention timestamps and effectiveness tracking
- Impact measurements on server activity

### 1.7 Boost System Configuration
- Custom boost announcement messages
- Boost notification channel settings
- Custom boost images and media
- Default/custom message preferences
- Boost system enable/disable states
- Boost logging channel configurations

### 1.8 Effect Command Data
#### Temporary Session Data
- User avatar URLs for effect processing
- Interactive menu states and user selections
- Effect preference choices during active sessions
- Active menu tracking to prevent duplicate sessions

#### Processing Information
- Avatar processing requests and results
- Effect application parameters
- Menu interaction timestamps

## 2. Purpose of Data Collection

We use the collected data to:

- **Core Bot Functionality:**
  - Operate giveaway systems with participant tracking
  - Provide welcome messages and greeting cards
  - Process and apply visual effects to user avatars
  - Maintain user preference settings
- **Server Analytics and Insights:**
  - Track member activity patterns and engagement
  - Analyze gaming trends and popular games
  - Measure the impact of server announcements
  - Provide server administrators with activity statistics
- **User Experience Enhancement:**
  - Maintain personalized settings and preferences
  - Prevent command conflicts through session management
  - Provide customizable server features
- **System Optimization:**
  - Improve bot performance and response times
  - Ensure stable operation across multiple servers

## 3. Data Retention Policies

### 3.1 Short-Term Data (Automatically Deleted)
- **Server tracking data:** Retained for **maximum 4 days**, then automatically purged
- **Effect command sessions:** Automatically cleared after **10 minutes** of inactivity
- **Temporary avatar processing data:** Deleted immediately after processing

### 3.2 Long-Term Data (Until Manual Deletion)
- **Giveaway configurations:** Persist until manually deleted by server administrators
- **Welcome/greeting settings:** Persist until manually removed or bot is removed from server
- **User preferences:** Persist until user requests deletion or modifies settings
- **Server boost configurations:** Persist until manually changed by administrators

### 3.3 Automatic Cleanup Systems
- Daily cleanup routines remove data older than retention periods
- Failed or incomplete sessions are automatically purged
- Orphaned data from deleted servers is regularly cleaned

## 4. Data Sharing and Third Parties

- **We DO NOT sell, share, or disclose your data to third parties**
- **We DO NOT use external services for avatar processing or effect generation**
- Data is only accessed by:
  - EvoBot's automated systems for functionality
  - Authorized developers for technical support and maintenance
  - Server administrators for their own server's data through bot commands

## 5. Security Measures

We implement comprehensive security practices:

- **Database Security:**
  - Secure database access with authentication
  - Encrypted connections for all data transmission
  - Regular security audits and updates
- **Access Control:**
  - Restricted access limited to authorized developers only
  - Multi-factor authentication for administrative access
  - Regular access reviews and permission updates
- **Data Protection:**
  - Automatic data purging and cleanup systems
  - Secure handling of temporary user data
  - No permanent storage of sensitive information like avatars
- **Session Management:**
  - Automatic cleanup of inactive command sessions
  - Prevention of data leaks through session isolation
  - Timeout mechanisms for all interactive features

## 6. Your Rights and Control

As a user or server administrator, you have the following rights:

### 6.1 Data Access and Control
- Request information about data stored for your server
- Modify or delete your user preferences at any time

### 6.2 Data Deletion Options
- **Complete removal:** Remove EvoBot from your server to delete all server-related data
- **Selective deletion:** Use bot commands to delete specific configurations
- **User settings:** Modify personal preferences through user commands
- **Support requests:** Contact our support team for manual data deletion

### 6.3 Feature Control
- Enable/disable individual bot features per server
- Customize privacy settings for personal features
- Opt out of specific tracking or analytics features

## 7. Effect Command Specific Information

### 7.1 How the Effect Command Works
- Requires users to have a Discord profile picture to function
- Temporarily accesses your avatar URL from Discord's servers
- Processes effects locally without external service involvement
- Creates interactive menus for effect selection

### 7.2 Data Handling for Effects
- **Avatar URLs:** Accessed in real-time, never permanently stored
- **Session data:** Temporarily stored during active use, auto-deleted after 10 minutes
- **Processing data:** Immediately discarded after effect application
- **Menu interactions:** Tracked only to prevent conflicts, automatically cleaned

### 7.3 Privacy Protection
- No avatar images are saved to our systems
- Effect processing happens in memory only
- Session isolation prevents data mixing between users
- Automatic cleanup ensures no data persistence

## 8. Gaming and Activity Tracking

### 8.1 What We Track
- Number of members playing games (not specific user identities)
- Popular games and player counts
- Activity patterns and peak times
- General server engagement metrics

### 8.2 What We DON'T Track
- Individual user gaming habits or preferences
- Specific user activity patterns
- Personal gaming statistics or achievements
- Private user information or behaviors

## 9. Children's Privacy

We are committed to protecting children's privacy:

- We do not knowingly collect data from users under 13
- If we discover data from a child under 13, we delete it immediately
- Parents can contact us to request deletion of their child's data
- We comply with COPPA and similar child protection regulations

## 10. Changes to This Policy

- We may update this Privacy Policy periodically to reflect changes in our practices
- Significant changes will be announced in our support server
- Continued use of EvoBot after changes indicates acceptance of updated terms
- Previous versions of this policy are available upon request

## 11. Data Breach Response

In the unlikely event of a data breach:

- We will immediately investigate and contain the incident
- Affected users and server administrators will be notified within 72 hours
- We will provide detailed information about what data was affected
- Steps to protect your information will be clearly communicated

## 12. GDPR Compliance

If you are located in the European Economic Area (EEA), you have the following data protection rights under the General Data Protection Regulation (GDPR):

- The right to access, update or delete the information we hold about you
- The right to data portability
- The right to object to processing
- The right to restrict processing
- The right to withdraw consent at any time (where applicable)
- The right to lodge a complaint with a data protection authority

To exercise these rights, please contact us using the information in section 13.

## 13. Contact Information

If you have questions about this Privacy Policy or our data practices:

- **Discord Support Server:** [https://discord.gg/evobot](https://discord.gg/evobot)
- **Response Time:** We typically respond to privacy inquiries within 48 hours.

---

**Last Updated:** 5 Jun 2025  
**Policy Version:** 2.0

*This Privacy Policy is effective immediately and supersedes all previous versions.*
