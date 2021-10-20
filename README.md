change comment {// days until deadline} place above {int d}

    // days until deadline
    int d;

delete unnecessary comment {// if the student is at least 18 years of age}
    
    if (student.Age> = 18)
    {
        // send meeting invitation to the student
        notificationService.SendMessageTo(student, meetingInvitation);
    }

delete unnecessary comment {// if the student is younger than 18 years}

    else
    {
        // sends a meeting invitation to the student's legal guardian
        notificationService.SendMessageTo(student.Parent, meetingInvitation);
    }
