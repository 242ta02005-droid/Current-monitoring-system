# Current-monitoring-system
# Current Monitoring System

MAX_CURRENT = 10  # Maximum safe current in Amps

print("==============================")
print("     CURRENT MONITORING SYSTEM")
print("==============================")

current = float(input("Enter current (A): "))

print("\nMeasured Current:", current, "A")
print("Maximum Safe Current:", MAX_CURRENT, "A")

if current > MAX_CURRENT:
    print("\n⚠️ OVERCURRENT DETECTED!")
    print("🔴 Protection System Activated")
    print("🔌 Load Disconnected")
else:
    print("\n🟢 CURRENT NORMAL")
    print("✅ Load Connected")
    print("System Operating Safely")
