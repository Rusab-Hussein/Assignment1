Dim mID As Integer
        Dim mName As String

        Console.Write("Enter member ID: ")
        mID = Console.ReadLine
        Console.Write("Enter Member name: ")
        mName = Console.ReadLine

        FileOpen(1, "D:\mRec.txt", OpenMode.Output)

        WriteLine(1, mID)
        WriteLine(1, mName)

        FileClose(1)
