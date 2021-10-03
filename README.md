//ПЕЧЕНКИН ДЕНИС

			//ЗАДАНИЕ 1 Написать программу «Анкета». Последовательно задаются вопросы (имя, фамилия, возраст, рост, вес). В результате вся информация выводится в одну строчку

			Console.WriteLine("Заполните анкету: ");

			Console.Write("Введите Ваше имя: ");
			string name = Console.ReadLine();

			Console.Write("Введите Вашу фамилию: ");
			string surname = Console.ReadLine();

			Console.Write("Введите Ваш возраст: ");
			string age = Console.ReadLine();

			Console.Write("Введите Ваш рост (см): ");
			string height = Console.ReadLine();

			Console.Write("Введите Ваш вес (кг): ");
			string weight = Console.ReadLine();

			//Склеивание
			Console.WriteLine("Ваши данные: " + name + " " + surname + ", " + age + " лет, рост " + height + " см., вес " + weight + " кг.");
			//Форматированный вывод
			//Console.WriteLine("Ваши данные: {0} {1}, {2} лет, рост {3} см., вес {4} кг.,", name, surname, age, height, weight);
			//$
			//Console.WriteLine($"Ваши данные: {name} {surname}, {age} лет, рост {height} см., вес {weight} кг.");

			Console.WriteLine("Спасибо за прохождение анкеты!");
			Console.WriteLine("*Чтобы продолжить нажмите Enter");
			Console.ReadLine();

			Console.Clear();
			
			
			//ЗАДАНИЕ 2 Ввести вес и рост человека. Рассчитать и вывести индекс массы тела (ИМТ) по формуле I=m/(h*h); где m — масса тела в килограммах, h — рост в метрах.

			Console.WriteLine("Введите Ваши данные, чтобы узнать индекс массы тела.");

			Console.Write("Введите Ваш рост (м.): ");
			string height2 = Console.ReadLine();
			double h = Double.Parse(height2);

			Console.Write("Введите Ваш вес (кг.): ");
			string weight2 = Console.ReadLine();
			double w = Double.Parse(weight2);

			double l = w / (h * h);

			Console.WriteLine("Ваш индекс массы тела: " + l);
			Console.WriteLine("*Чтобы продолжить нажмите Enter");
			Console.ReadLine();

			Console.Clear();


			//ЗАДАНИЕ 5 Написать программу, которая выводит на экран ваше имя, фамилию и город проживания.
			//б) Сделать задание, только вывод организовать в центре экрана.
			Console.WriteLine();
			string name2 = "Денис";
			string surname2 = "Печенкин";
			string city = "Санкт-Петербург";

			Console.SetCursorPosition(85, 4);
			Console.WriteLine(name2);
			Console.SetCursorPosition(85, 5);
			Console.WriteLine(surname2);
			Console.SetCursorPosition(85, 6);
			Console.WriteLine(city);
