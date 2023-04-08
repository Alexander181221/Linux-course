   15 mkdir students

   16  mkdir mentors

   17  ll

   18  cd students/

   19  touch sudents_list.txt

   20  cd ..

   21  cd mentors

   22  touch mentors_list.txt

   23  ll

   24  nano mentors_list.txt 

   25  cd ..

   26  cd students

   27  nano students_list.txt

   28  cd .. 

   29  ll

   30  cd mentors

   31  mv *.txt /home/alexvoyt/students

   32  ll

   33  cd ..

   34  cd students

   35  ll

   36  cat sudents_list.txt 

   37  cat students_list.txt 

   38  rm sudents_list.txt 

   39  ll

   40  cd ..

   41  ll

   42  mv students students_and_mentors

   43  ll

   44  rm mentors -f

   45  rm -f mentors

   46  rmdit mentors

   47  rmdir mentors

   48  ll

   49  cat > file1 

   50  cp file1 file2

   51  ll

   52  ln -s file2 file3

   53  ll

   54  ln file1 file4

   55  ll

   56  rm file4

   57  ll

   58  ln file4 file1

   59  ln file1 file4

   60  ll

   61  ll -i

   62  ll

   63  cat file3

   64  cat file2

   65  cat file4

   66  ll

   67  mv file3 softlink_to_file2

   68  mv file4 hardlink_to_file1

   69  ll

   70  mv file1 original_file1

   71  mv file2 otiginal_file2

   72  ll

   73  mv otiginal_file2 original_file2

   74  ll

   75  ln -s softlink_to_file2 original_file2

   76  ln -s softlink_to_file2 new_softlink

   77  ll

   78  rm new_softlink 

   79  ll

   80  ln -s original_file2 new_softlink

   81  ll

   82  mkdir mytestdir

   83  ll

   84  mv original_file1 original_file2 new_softlink softlink_to_file2 /home/alexvoyt/mytestdir  

   85  ll

   86  cd mytestdir

   87  ll

   88  ll -i

   89  cd ..

   90  ll

