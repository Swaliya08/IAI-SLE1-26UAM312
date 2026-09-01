# IAI-SLE1-26UAM312
SLE-1 Basic AI Agent Project
print("===== Student Study Recommendation Agent =====")

print("\nWhat is your current situation?")
print("1. My exam is tomorrow")
print("2. My exam is next week")
print("3. I am tired")
print("4. I don't understand a topic")

choice = input("\nEnter your choice (1-4): ")

if choice == "1":
    print("\nRecommendation: Focus on revision and important topics.")

elif choice == "2":
    print("\nRecommendation: Make a study plan and study regularly.")

elif choice == "3":
    print("\nRecommendation: Take a short break and then continue studying.")

elif choice == "4":
    print("\nRecommendation: Review the basics and ask your teacher for help.")

else:
    print("\nInvalid choice. Please enter a number from 1 to 4.")
