# Studying-for-exams


``` mermaid
journey
	title Me studying for exams
	section Exam is announced
		I start studying: 1: Me
		Make notes: 2: Me
		Ask friend for help: 3: Me, Friend
		We study togther: 5: Me, Friend
	section Exam Day
		Syllabys is incomplete: 2: Me
		Give exam: 1: Me, Friend
	section Result Declared
		I passed the exam with destinction!: 5: Me
		Friend barely gets passing marks: 2: Friend
```

``` mermaid
journey
	title dRecords is a practitioner web-application to manage patients their medical records and appointments
	section Practitioner is registered
		Practitioner logs-in and views my patients list: 1: Practitioner
		Practitioner chooses a particular patient from the list: 2: Practitioner
		Practitioner writes notes, reads medical details and diagnosis on patient: 3: Practitioner, Patient
		Practitioner books an appointment with a patient using calendar, email is sent: 5: Practitioner, Patient
	section Patients email
		Patient receives email: 2: Patient
		Patient confirms or cancels email by calling clinic: 1: Practitioner, Patient
	section Patients visits appointment
		Practitioner is able to chart and update notes on patient: 5: Practitioner
		Practitioner updates health info and logs out, erasing session id: 2: Patient
```
