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
	section Practitioner using drecords web-app
		logs-in and views my patients list: 1: Practitioner
		chooses a particular patient from the list: 2: Practitioner
		charts, reads medical details and diagnosis on patient: 3: Practitioner, Patient
		books a calendar appointment with a patient, email is sent: 5: Practitioner, Patient
	section Patient check their email
		receives email: 2: Patient
		informed of appointment or cancels by calling: 1: Practitioner, Patient
	section Patients visits appointment
		is able to chart and update notes on patient: 5: Practitioner
		updates drecords, logs out nulling session id: 2: Patient
```
