# ✂️ Salon Appointment Scheduler

A PostgreSQL-backed Bash application for managing salon appointments and customers, created for freeCodeCamp's Relational Database certification.

## 📋 Project Overview
- **Database**: PostgreSQL
- **Interface**: Interactive Bash script
- **Features**:
  - Manage customers and appointments
  - Track services and schedules
  - Simple terminal-based UI

## 📂 Required Files
| File | Purpose |
|------|---------|
| `salon.sql` | Database dump with all tables and schema |
| `salon.sh` | Main Bash script for the scheduler |

## 🚀 Quick Setup
```bash
# 1. Clone the repository
git clone https://github.com/Rida-Lad/salon-scheduler.git
cd salon-scheduler

# 2. Import the database
psql -U postgres -f salon.sql

# 3. Make the script executable
chmod +x salon.sh

# 4. Run the application
./salon.sh
