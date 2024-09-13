while True:
    # إدخال اختيار المستخدم
    choice = input("أدخل اختيارك (1/2/3/4): ")

    # التحقق من صحة الاختيار
    if choice in ['1', '2', '3', '4']:
        num1 = float(input("أدخل الرقم الأول: "))
        num2 = float(input("أدخل الرقم الثاني: "))

        if choice == '1':
            print(f"النتيجة: {add(num1, num2)}")

        elif choice == '2':
            print(f"النتيجة: {subtract(num1, num2)}")

        elif choice == '3':
            print(f"النتيجة: {multiply(num1, num2)}")

        elif choice == '4':
            print(f"النتيجة: {divide(num1, num2)}")
    else:
        print("اختيار غير صحيح، حاول مرة أخرى.")

    # نسأل المستخدم إذا كان يريد إجراء عملية أخرى
    next_calculation = input("هل تريد إجراء عملية أخرى؟ (نعم/لا): ")
    if next_calculation.lower() != 'نعم':
        break# Calculator-
آلة حاسبة 
