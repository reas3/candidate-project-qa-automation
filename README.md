# Test Cases

## 1. Page Loads Successfully
- **Given** I am a guest user
- **When** I navigate to `https://www.zoomcare.com/schedule`
- **Then** the page should load without errors, and the schedule search interface should be visible

## 2. Location Filter - Search by City
- **Given** I am on the schedule page
- **When** I search for “Portland”
- **Then** the available appointment locations and slots should update to reflect Portland-based clinics

## 3. Location Filter - Invalid Input
- **Given** I am on the schedule page
- **When** I enter an invalid location like “Atlantis”
- **Then** a message like “No appointments available” should be displayed

## 4. Service Type Filter
- **Given** I am on the schedule page
- **When** I select the “Illness & Injury” filter
- **Then** only relevant appointments for that service should be shown

## 5. Date Picker
- **Given** I am on the schedule page
- **When** I change the date using the calendar control
- **Then** the appointment slots should update for the selected date

## 6. Time Slot Click Redirect
- **Given** I am on the schedule page
- **When** I click a time slot
- **Then** I should be redirected to the login or signup page

## 7. Auto-Refresh Behavior
- **Given** I have had the schedule page open for more than 5 minutes
- **When** slots change in the backend
- **Then** the page should refresh or notify the user to refresh

## 8. Responsive Design - Mobile View
- **Given** I view the schedule page on a mobile device
- **Then** the page should adapt and be fully usable (filters, date picker, time slots)

## 9. URL Reflects Filters
- **Given** I apply a location and service filter
- **Then** the URL should update to reflect those filters (e.g., query parameters)


__________________________________________________________________



# Automation Instructions

(We will complete this in Part 2)
