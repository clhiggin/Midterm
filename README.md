# Midterm
//Contains answer midterm

using System;
using System.Collections.Generic;
using System.Text;

namespace MidtermQ5
{
	class MyFavSubject
	{
		public string name;
		public string subject;
		public void readers(string name, string subject)
		{
			this.name = name;
			this.subject = subject;
			Console.WriteLine("Myself: " + name);
			Console.WriteLine("My Favorite Subject is: " + subject);
		}
	}

		class StudentForStudent : MyFavSubject 
		{
		public StudentForStudent()
		{
			Console.WriteLine("StudentForStudent");
		}
	}

	class ExperienceIT
	{
		static void Main(string[] args)
		{
			StudentForStudent g = new StudentForStudent();
			g.readers("Crystal", "C#");
		}
	}
}


