Steps for first time file creation, initializing git, commit and pushing

echo "# googleSheet" >> sprintCapacityTracker.txt
git add sprintCapacityTracker.txt               
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/Nahidahmed/googleSheet.git
git push -u origin main


Notes for setting up Sprint Capacity sprintCapacityTracker

1. Make sure you first create below 3 worksheets with same name
    a. Base Info
    b. Capacity Overview
    c. Sprints 2025
2. To setup the sprints do below Steps
    a. Keep the worksheet, "Sprints 2025" active
    b. Run the function - generateSprint2025()
3. To setup the capacity overview do below Steps
    a. Keep the worksheet, "Capacity Overview" active
    b. Run the function - capacityOverview()
4. The example script is based on master data on the worksheet, "Base Info". If data changes in this worksheet, make changes on functions accordingly.
