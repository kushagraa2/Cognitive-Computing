{
 "cells": [
  {
   "cell_type": "markdown",
   "id": "0cc83f88-9697-462d-b25d-6a0ceb4a8f22",
   "metadata": {},
   "source": [
    "## Printing Text"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 2,
   "id": "b31da05a-ecae-4a1e-9fd3-94614d297f45",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Hello Everyone\n"
     ]
    }
   ],
   "source": [
    "print('Hello Everyone')"
   ]
  },
  {
  
   "cell_type": "markdown",
   "id": "4f7aac4c-e95d-46c2-af83-7e5c6d46e2cf",
   "metadata": {},
   "source": [
    "### Assignment 1.1"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 3,
   "id": "1b1ac6e2-fbdc-44bb-a090-2b83cf407e50",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Kushagra Khattri\n",
      "Kushagra Khattri\n",
      "Kushagra Khattri\n"
     ]
    }
   ],
   "source": [
    "print('Kushagra Khattri')\n",
    "print('AKushagra Khattri')\n",
    "print('Kushagra Khattri')"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "dd0af04d-5e0d-4c41-bdf5-acd74ec02a5a",
   "metadata": {},
   "source": [
    "## Add numbers and Concatinate strings"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 4,
   "id": "55c9efcb-066c-41fc-a5ed-f1712e15f4ea",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "10 + 20 = 30\n"
     ]
    }
   ],
   "source": [
    "a=10\n",
    "b=20\n",
    "c=a+b\n",
    "print(a,'+',b,'=',c)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 8,
   "id": "30579fd1-dbc0-452a-b537-6914b94da331",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Kushagra + Khattri = Kushagra Khattri\n"
     ]
    }
   ],
   "source": [
    "a='Kushagra'\n",
    "b=' Khattri'\n",
    "c=a+b\n",
    "print(a,'+',b,'=',c)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 9,
   "id": "156311ff-d968-43e8-b34e-c0c6b65ab310",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Kushagra + 20 = Kushagra20\n"
     ]
    }
   ],
   "source": [
    "a='Kushagra'\n",
    "b=20\n",
    "c=a+str(b)\n",
    "print(a,'+',b,'=',c)"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "935abce1-cf8b-44d7-9721-9dd542369cd9",
   "metadata": {},
   "source": [
    "### Assignment 2.1"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 10,
   "id": "8e89a5d3-e9e1-4db9-9471-6a3eac46899c",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "10 + 20 + 30 = 60\n"
     ]
    }
   ],
   "source": [
    "a=10\n",
    "b=20\n",
    "c=30\n",
    "d=a+b+c\n",
    "print(a,'+',b,'+',c,'=',d)"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "792894fd-3e3f-4e3d-979a-25942c209334",
   "metadata": {},
   "source": [
    "### Assignment 2.2"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "f126a7ab-e26b-4544-b4e4-2482d0764b8e",
   "metadata": {},
   "outputs": [],
   "source": [
    "a=10\n",
    "b=20\n",
    "c=30\n",
    "d=a+b+c\n",
    "print(a,'+',b,'+',c,'=',d)"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "abb572f0-95eb-487e-a743-94188549283e",
   "metadata": {},
   "source": [
    "## Input from user"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 11,
   "id": "91cbecdb-c8c8-4086-beb8-adada812b49d",
   "metadata": {},
   "outputs": [
    {
     "name": "stdin",
     "output_type": "stream",
     "text": [
      "enter first string:  Hello\n",
      "enter second string:  World\n"
     ]
    },
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Hello  +  World = HelloWorld\n"
     ]
    }
   ],
   "source": [
    "x = input('enter first string: ')\n",
    "y = input('enter second string: ')\n",
    "z = x + y\t\n",
    "print  (x, \" + \", y, \"=\", z)\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 13,
   "id": "fab2c621-0411-4284-8613-f7805b52277c",
   "metadata": {},
   "outputs": [
    {
     "name": "stdin",
     "output_type": "stream",
     "text": [
      "enter first number:  10\n",
      "enter second number:  20\n"
     ]
    },
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "10  +  20 = 30\n"
     ]
    }
   ],
   "source": [
    "x = int(input('enter first number: '))\n",
    "y = int(input('enter second number: '))\n",
    "z = x + y\t\n",
    "print  (x, \" + \", y, \"=\", z)\n"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "fb089d66-028e-4ea6-b167-fb9d392f6bb4",
   "metadata": {},
   "source": [
    "## Loops"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 16,
   "id": "51843779-905e-4955-bfef-9251a9d56e56",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "1\n",
      "2\n",
      "3\n",
      "4\n",
      "5\n",
      "6\n",
      "7\n",
      "8\n",
      "9\n",
      "10\n",
      "11\n",
      "12\n",
      "13\n",
      "14\n",
      "15\n"
     ]
    }
   ],
   "source": [
    "i=1\n",
    "while i<=15:\n",
    "    print(i)\n",
    "    i=i+1"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 19,
   "id": "5d5ff524-2167-47a5-a2f2-6af9cde912f0",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "range(10)        -->  [0, 1, 2, 3, 4, 5, 6, 7, 8, 9]\n",
      "range(10,20)     -->  [10, 11, 12, 13, 14, 15, 16, 17, 18, 19]\n",
      "range(0,20,2)    -->  [0, 2, 4, 6, 8, 10, 12, 14, 16, 18]\n",
      "range(-10,-20,2) -->  []\n",
      "range(-10,-20,-2)-->  [-10, -12, -14, -16, -18]\n"
     ]
    }
   ],
   "source": [
    "print (\"range(10)        --> \", list(range(10)))\n",
    "print (\"range(10,20)     --> \", list(range(10,20)))\n",
    "print (\"range(0,20,2)    --> \", list(range(0,20,2)))\n",
    "print (\"range(-10,-20,2) --> \", list(range(-10,-20,2)))\n",
    "print (\"range(-10,-20,-2)--> \", list(range(-10,-20,-2)))"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 21,
   "id": "b06bd29d-65ec-433d-a591-ea2b812bc754",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "0\n",
      "1\n",
      "2\n",
      "3\n",
      "4\n",
      "5\n",
      "6\n",
      "7\n",
      "8\n",
      "9\n"
     ]
    }
   ],
   "source": [
    "for i in range(0,10):\n",
    "    print(i)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 22,
   "id": "5211ce08-58e8-41b4-8877-afae17b35620",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "0\n",
      "2\n",
      "4\n",
      "6\n",
      "8\n",
      "10\n",
      "12\n",
      "14\n",
      "16\n",
      "18\n"
     ]
    }
   ],
   "source": [
    "for i in range(0,20,2):\n",
    "    print(i)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 24,
   "id": "f8ee5084-3869-428a-b345-8b80959ff941",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "0\n",
      "3\n",
      "6\n",
      "9\n",
      "12\n",
      "15\n",
      "18\n"
     ]
    }
   ],
   "source": [
    "for i in range(0,20,3):\n",
    "    print(i)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 26,
   "id": "15c98add-3f26-4ca1-9a3f-2eacc2bea428",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "6  *  1  =  6\n",
      "6  *  2  =  12\n",
      "6  *  3  =  18\n",
      "6  *  4  =  24\n",
      "6  *  5  =  30\n",
      "6  *  6  =  36\n",
      "6  *  7  =  42\n",
      "6  *  8  =  48\n",
      "6  *  9  =  54\n",
      "6  *  10  =  60\n"
     ]
    }
   ],
   "source": [
    "for i in range(1,11):\n",
    "    print(6,\" * \", i , \" = \", i * 6)"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "5b914860-b264-4269-be4b-ce7e141663aa",
   "metadata": {},
   "source": [
    "### Sum "
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 28,
   "id": "928f3d47-424c-4b5a-bdce-fa73fae37950",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Sum is:  55\n"
     ]
    }
   ],
   "source": [
    "s=0\n",
    "for i in range(1,11):\n",
    "    s=s+i\n",
    "print(\"Sum is: \",s)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 29,
   "id": "3df3655f-4c7e-4be3-bb49-e0dbc1599940",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Sum is:  55\n"
     ]
    }
   ],
   "source": [
    "print(\"Sum is: \",sum(range(1,11)))"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "d0861933-bec4-416a-a917-e9a8b33d3bc9",
   "metadata": {},
   "source": [
    "### Assignment 4.1"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 30,
   "id": "759cbba9-afda-4663-ae66-07881f7fd98a",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "7  *  1  =  7\n",
      "7  *  2  =  14\n",
      "7  *  3  =  21\n",
      "7  *  4  =  28\n",
      "7  *  5  =  35\n",
      "7  *  6  =  42\n",
      "7  *  7  =  49\n",
      "7  *  8  =  56\n",
      "7  *  9  =  63\n",
      "7  *  10  =  70\n"
     ]
    }
   ],
   "source": [
    "for i in range(1,11):\n",
    "    print(7,\" * \", i , \" = \", i * 7)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 31,
   "id": "3fef30ec-5eea-49e3-b94a-95bdf0448b4f",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "9  *  1  =  9\n",
      "9  *  2  =  18\n",
      "9  *  3  =  27\n",
      "9  *  4  =  36\n",
      "9  *  5  =  45\n",
      "9  *  6  =  54\n",
      "9  *  7  =  63\n",
      "9  *  8  =  72\n",
      "9  *  9  =  81\n",
      "9  *  10  =  90\n"
     ]
    }
   ],
   "source": [
    "for i in range(1,11):\n",
    "    print(9,\" * \", i , \" = \", i * 9)"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "36333740-8386-4041-bb36-917bdc089ddb",
   "metadata": {},
   "source": [
    "### Assignment 4.2"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 32,
   "id": "eae78dc4-7113-459c-ae8b-13c95f476db5",
   "metadata": {},
   "outputs": [
    {
     "name": "stdin",
     "output_type": "stream",
     "text": [
      "enter any number:  4\n"
     ]
    },
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "4  *  1  =  4\n",
      "4  *  2  =  8\n",
      "4  *  3  =  12\n",
      "4  *  4  =  16\n",
      "4  *  5  =  20\n",
      "4  *  6  =  24\n",
      "4  *  7  =  28\n",
      "4  *  8  =  32\n",
      "4  *  9  =  36\n",
      "4  *  10  =  40\n"
     ]
    }
   ],
   "source": [
    "n = int(input(\"enter any number: \"))\n",
    "for i in range(1,11):\n",
    "    print(n,\" * \", i , \" = \", i * n)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 34,
   "id": "77c5e084-58ca-49cf-b29a-46093d52e2a8",
   "metadata": {},
   "outputs": [
    {
     "name": "stdin",
     "output_type": "stream",
     "text": [
      "enter any number:  4\n"
     ]
    },
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "6\n"
     ]
    }
   ],
   "source": [
    "n = int(input(\"enter any number: \"))\n",
    "s=0\n",
    "for i in range(1,n):\n",
    "    s=s+i\n",
    "print(s)"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "5c0f7f39-438e-4972-b0e2-3f93599b8216",
   "metadata": {},
   "source": [
    "## If-Else Conditions"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 42,
   "id": "38140a0a-23ae-4ae8-8300-a80bf7bd4f32",
   "metadata": {},
   "outputs": [
    {
     "name": "stdin",
     "output_type": "stream",
     "text": [
      "Enter first number:  78\n",
      "Enter second number:  54\n"
     ]
    },
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "78  >  54\n"
     ]
    }
   ],
   "source": [
    "a = int(input(\"Enter first number: \"))\n",
    "b = int(input(\"Enter second number: \"))\n",
    "if  a > b:\n",
    "\tprint (a,\" > \",b)\n",
    "else:\n",
    "\tprint (a,\" < \",b)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 41,
   "id": "f18b0542-f8e9-4fed-9667-901e9012a03d",
   "metadata": {},
   "outputs": [
    {
     "name": "stdin",
     "output_type": "stream",
     "text": [
      "Enter a number:  34\n"
     ]
    },
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "34  is even\n"
     ]
    }
   ],
   "source": [
    "n = int(input(\"Enter a number: \"))\n",
    "if  n % 2 == 0:\n",
    "\tprint (n,\" is even\")\n",
    "else:\n",
    "\tprint (n,\" is odd\")"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 40,
   "id": "02f9c5ed-3334-493f-a2f8-e8f31caa09c6",
   "metadata": {},
   "outputs": [
    {
     "name": "stdin",
     "output_type": "stream",
     "text": [
      "Enter a number:  45\n"
     ]
    },
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Not Prime number\n"
     ]
    }
   ],
   "source": [
    "n = int(input(\"Enter a number: \"))\n",
    "f=0\n",
    "for i in range(2, n//2 + 1):\n",
    "\tif  n % i == 0:\n",
    "\t\tf=1\n",
    "\t\tbreak\n",
    "\n",
    "if f==0:\n",
    "\tprint (\"Prime number\")\n",
    "else:\n",
    "\tprint (\"Not Prime number\")"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 43,
   "id": "a1d49d22-723d-4652-b937-a16734610999",
   "metadata": {},
   "outputs": [
    {
     "name": "stdin",
     "output_type": "stream",
     "text": [
      "Enter first string :  hello\n",
      "Enter second string:  world\n"
     ]
    },
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "a < b\n"
     ]
    }
   ],
   "source": [
    "a = input(\"Enter first string : \")\n",
    "b = input(\"Enter second string: \")\n",
    "\n",
    "if a == b:\n",
    "\tprint (\"a == b\")\n",
    "elif a >= b:\n",
    "\tprint (\"a > b\")\n",
    "else:\n",
    "\tprint (\"a < b\")"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "01e3557c-0f2e-48c0-aa21-37f56cc7a438",
   "metadata": {},
   "source": [
    "### Assignment 5.1"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 47,
   "id": "867ec579-8bc6-43d7-8346-484fbe60e66c",
   "metadata": {},
   "outputs": [
    {
     "name": "stdin",
     "output_type": "stream",
     "text": [
      "enter first number:  4\n",
      "enter second number:  5\n",
      "enter third number:  6\n"
     ]
    },
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "6 is maximum\n"
     ]
    }
   ],
   "source": [
    "x = int(input('enter first number: '))\n",
    "y = int(input('enter second number: '))\n",
    "z = int(input('enter third number: '))\n",
    "\n",
    "if x==y==z:\n",
    "    print('all are equal')\n",
    "elif x>=y and x>=z:\n",
    "    print(x,'is maximum')\n",
    "elif y>=z and y>=x:\n",
    "    print(y,'is maximum')\n",
    "else:\n",
    "    print(z,'is maximum')"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 56,
   "id": "233c4cc7-35ae-4b76-9126-ee73db87495a",
   "metadata": {},
   "outputs": [
    {
     "name": "stdin",
     "output_type": "stream",
     "text": [
      "enter first number:  3\n",
      "enter second number:  4\n",
      "enter third number:  5\n"
     ]
    },
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Maximum is:  5\n"
     ]
    }
   ],
   "source": [
    "x = int(input('enter first number: '))\n",
    "y = int(input('enter second number: '))\n",
    "z = int(input('enter third number: '))\n",
    "\n",
    "print('Maximum is: ',max(x,y,z))"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "b4b25b20-19e5-4f17-bfd2-87c485b2dde5",
   "metadata": {},
   "source": [
    "### Assignment 5.2"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 49,
   "id": "e77c51c8-18a6-4f31-894c-56259b513d78",
   "metadata": {},
   "outputs": [
    {
     "name": "stdin",
     "output_type": "stream",
     "text": [
      "enter any number:  128\n"
     ]
    },
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "189\n"
     ]
    }
   ],
   "source": [
    "n = int(input('enter any number: '))\n",
    "s = 0\n",
    "for i in range(1,n):\n",
    "    if i%7==0 and i%9==0:\n",
    "        s=s+i\n",
    "print(s)"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "3bad313d-7a04-45be-9660-0c4d81dd30bd",
   "metadata": {},
   "source": [
    "### Assignment 5.3"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 55,
   "id": "61f8019a-205c-4053-a594-e74c1216eb4a",
   "metadata": {},
   "outputs": [
    {
     "name": "stdin",
     "output_type": "stream",
     "text": [
      "Enter a number:  11\n"
     ]
    },
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Sum of prime numbers from 1 to 11 is: 28\n"
     ]
    }
   ],
   "source": [
    "n = int(input(\"Enter a number: \"))\n",
    "sum_primes = 0\n",
    "\n",
    "for num in range(2, n + 1):\n",
    "    is_prime = True\n",
    "\n",
    "    for i in range(2, num//2 + 1):\n",
    "        if num % i == 0:\n",
    "            is_prime = False\n",
    "            break\n",
    "\n",
    "    if is_prime:\n",
    "        sum_primes += num\n",
    "\n",
    "print(\"Sum of prime numbers from 1 to\", n, \"is:\", sum_primes)"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "d1c9041f-dca6-460f-b166-c3effb6bb72a",
   "metadata": {},
   "source": [
    "## Functions"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 59,
   "id": "ba12a324-fb65-4557-95ca-31442ee1afd4",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Add(30,40)---> 70\n",
      "Add(100,80)---> 180\n"
     ]
    }
   ],
   "source": [
    "def Add(a,b):\n",
    "    c=a+b\n",
    "    return c\n",
    "print(\"Add(30,40)--->\",Add(30,40))\n",
    "print(\"Add(100,80)--->\",Add(100,80))"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 60,
   "id": "8a715a41-b87e-4f3c-8582-09332ccf417a",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "IsPrime(45) --> 0\n",
      "IsPrime(67) --> 1\n"
     ]
    }
   ],
   "source": [
    "def IsPrime(n):\n",
    "\tfor i in range(2, n//2 + 1):\n",
    "\t\tif n%i==0:\n",
    "\t\t\treturn 0\n",
    "\treturn 1\n",
    "\n",
    "print(\"IsPrime(45) -->\",IsPrime(45))\n",
    "print(\"IsPrime(67) -->\",IsPrime(67))"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 61,
   "id": "7903587c-8052-41e6-b83f-88da4da44500",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "AddN(12)  -->  78\n",
      "AddN(30)  -->  465\n"
     ]
    }
   ],
   "source": [
    "def AddN(n):\n",
    "\ts= sum(range(n+1))\n",
    "\treturn s\n",
    "\n",
    "print (\"AddN(12)  --> \", AddN(12))\n",
    "print (\"AddN(30)  --> \", AddN(30))"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 63,
   "id": "07cee61e-bd9e-4424-85d6-f1488dc41ec6",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Sum of odd numbers: 100\n"
     ]
    }
   ],
   "source": [
    "def sum_odd(n):\n",
    "    sum = 0\n",
    "    for i in range(1, n + 1):\n",
    "        if i % 2 != 0:\n",
    "            sum += i\n",
    "    return sum\n",
    "\n",
    "print(\"Sum of odd numbers:\", sum_odd(20))"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 64,
   "id": "9d50fe7d-044f-44e0-b155-d38dc03b7342",
   "metadata": {},
   "outputs": [
    {
     "name": "stdin",
     "output_type": "stream",
     "text": [
      "Enter a number:  34\n"
     ]
    },
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Sum of prime numbers = 160\n"
     ]
    }
   ],
   "source": [
    "def is_prime(num):\n",
    "    if num < 2:\n",
    "        return False\n",
    "\n",
    "    for i in range(2, num//2 + 1):\n",
    "        if num % i == 0:\n",
    "            return False\n",
    "\n",
    "    return True\n",
    "\n",
    "def sum_prime(n):\n",
    "    total = 0\n",
    "\n",
    "    for i in range(2, n + 1):\n",
    "        if is_prime(i):\n",
    "            total += i\n",
    "\n",
    "    return total\n",
    "\n",
    "n = int(input(\"Enter a number: \"))\n",
    "print(\"Sum of prime numbers =\", sum_prime(n))"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "cc5d553a-0817-4acd-bd91-2de39454db03",
   "metadata": {},
   "source": [
    "## Math Library"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 65,
   "id": "a8b8981c-935d-4233-b2e5-0e620c5a76b9",
   "metadata": {},
   "outputs": [],
   "source": [
    "import math as m"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 66,
   "id": "bba1fff5-11c9-4f1a-bb82-066e03683e5d",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "exp(-200)    -->  1.3838965267367376e-87\n",
      "log(100,2)   -->  6.643856189774725\n",
      "log(100,10)  -->  2.0\n",
      "log10(100)   -->  2.0\n",
      "m.cos(30)    -->  0.15425144988758405\n",
      "m.sin(30)    -->  -0.9880316240928618\n",
      "m.tan(30)    -->  -6.405331196646276\n",
      "m.sqrt(324)  -->  18.0\n",
      "m.ceil(89.9) -->  90\n",
      "m.floor(89.9)-->  89\n"
     ]
    }
   ],
   "source": [
    "print (\"exp(-200)    --> \", m.exp(-200))  \n",
    "print (\"log(100,2)   --> \", m.log(100,2)) \n",
    "print (\"log(100,10)  --> \", m.log(100,10))\n",
    "print (\"log10(100)   --> \", m.log10(100))\n",
    "print (\"m.cos(30)    --> \", m.cos(30))    \n",
    "print (\"m.sin(30)    --> \", m.sin(30))    \n",
    "print (\"m.tan(30)    --> \", m.tan(30))    \n",
    "print (\"m.sqrt(324)  --> \", m.sqrt(324))\n",
    "print (\"m.ceil(89.9) --> \", m.ceil(89.9))\n",
    "print (\"m.floor(89.9)--> \", m.floor(89.9))"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "9a21314a-edf0-4bb3-906f-39d711d06740",
   "metadata": {},
   "source": [
    "## Strings"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 67,
   "id": "3d9b0020-a4f3-4281-ae3f-91a9029e571c",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "var      -->  Kushagra\n",
      "var[0]   -->  K\n",
      "var[1:5] -->  usha\n",
      "var[:-5] -->  Ku\n"
     ]
    }
   ],
   "source": [
    "var = 'Kushagra'\n",
    "print (\"var      --> \", var)\n",
    "print (\"var[0]   --> \", var[0])\n",
    "print (\"var[1:5] --> \", var[1:5])\n",
    "print (\"var[:-5] --> \", var[:-5])"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 68,
   "id": "08c13031-ac67-4f90-92c4-3576519af043",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "String -->  Kushagra Khattri\n",
      "Length --> :  13\n",
      "Upper  --> : KUSHAGRA KHATTRI\n",
      "Lower  --> :  kushagra khattri\n"
     ]
    }
   ],
   "source": [
    "var = 'Kushagra Khattri'\n",
    "print (\"String --> \", var)\n",
    "print (\"Length --> : \", len(var))\n",
    "print (\"Upper  --> : \", var.upper())\n",
    "print (\"Lower  --> : \", var.lower())"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 69,
   "id": "6a3f2e34-9baf-4993-bf29-dcb75c378f4c",
   "metadata": {},
   "outputs": [
    {
     "name": "stdin",
     "output_type": "stream",
     "text": [
      "Enter your name:  Kushagra\n",
      "Enter your age :  20\n",
      "Enter the book price:  19.6\n"
     ]
    },
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "\n",
      "Your name is KUSHAGRA, age is 20 and book price is 19.600000\n"
     ]
    }
   ],
   "source": [
    "name=input(\"Enter your name: \")\n",
    "age=int(input(\"Enter your age : \"))\n",
    "price=float(input(\"Enter the book price: \"))\n",
    "s=\"\\nYour name is %s, age is %d and book price is %f\" %(name.upper(),age,price)\n",
    "print (s)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 70,
   "id": "886edc24-7afe-478d-979e-50600d957b0f",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "This is a long string that is made up of several lines \n",
      "and non-printable characters such as TAB(\t)and they will show up when displayed.\n",
      "NEWLINEs within the string, whether explicitly given like this within the brackets[\n",
      "], \n",
      "or just a NEWLINE within the variable assignment will also show up. \n"
     ]
    }
   ],
   "source": [
    "para_str=\"\"\"This is a long string that is made up of several lines \n",
    "and non-printable characters such as TAB(\\t)and they will show up when displayed.\n",
    "NEWLINEs within the string, whether explicitly given like this within the brackets[\\n], \n",
    "or just a NEWLINE within the variable assignment will also show up. \"\"\"\n",
    "print(para_str)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 72,
   "id": "b4bf6fc9-1d64-43d2-958d-1636e183a81f",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "String    -->  Cognitive     Computing     \n",
      "Length    -->  28\n",
      "var strip -->  Cognitive     Computing\n",
      "Length of var after strip -->  23\n"
     ]
    }
   ],
   "source": [
    "var =\"Cognitive     Computing     \"\n",
    "\n",
    "print(\"String    --> \", var)\n",
    "print(\"Length    --> \", len(var))\n",
    "print(\"var strip --> \", var.strip())    # removes leading and trailing whitespace\n",
    "print(\"Length of var after strip --> \", len(var.strip()))"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 74,
   "id": "34e47940-b7e2-43ea-b882-7047b0ec1a24",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "String    -->  Cognitive,    Computing    \n",
      "Length    -->  27\n",
      "var split -->  ['Cognitive,', 'Computing']\n",
      "var split -->  ['Cognitive,', '', '', '', 'Computing', '', '', '', '']\n",
      "var split -->  ['Cognitive', '    Computing    ']\n",
      "var split -->  ['Cognitive', '    Computing']\n"
     ]
    }
   ],
   "source": [
    "var =\"Cognitive,    Computing    \"\n",
    "\n",
    "print(\"String    --> \", var)\n",
    "print(\"Length    --> \", len(var))\n",
    "print(\"var split --> \", var.split())   # breaks a string into a list of substrings based on a delimiter\n",
    "print(\"var split --> \", var.split(' '))\n",
    "print(\"var split --> \", var.split(','))\n",
    "\n",
    "# Strip + Split\n",
    "print(\"var split --> \", var.strip().split(','))"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 78,
   "id": "9e3eec2c-dc18-4631-a069-d9fce4e13e8e",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "String       -->  Cognitive Computing\n",
      "Count of ' ' -->  1\n",
      "Count of 'i' -->  3\n",
      "Count of 'it' -->  1\n"
     ]
    }
   ],
   "source": [
    "var=\"Cognitive Computing\"\n",
    "print (\"String       --> \", var)\n",
    "print (\"Count of ' ' --> \", var.count(' '))\n",
    "print (\"Count of 'i' --> \", var.count('i'))\n",
    "print (\"Count of 'it' --> \", var.count('it'))"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 79,
   "id": "2210bea1-2224-47cd-98ed-8c75e7f87966",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "String    -->  Cognitive Computing\n",
      "var[::1]  -->  Cognitive Computing\n",
      "var[::2]  -->  CgiieCmuig\n",
      "var[::-1] -->  gnitupmoC evitingoC\n",
      "var[::-2] -->  giumCeiigC\n",
      "var after reverse -->  gnitupmoC evitingoC\n"
     ]
    }
   ],
   "source": [
    "var=\"Cognitive Computing\"\n",
    "print (\"String    --> \", var)\n",
    "print (\"var[::1]  --> \", var[::1])\n",
    "print (\"var[::2]  --> \", var[::2])\n",
    "print (\"var[::-1] --> \", var[::-1])\n",
    "print (\"var[::-2] --> \", var[::-2])\n",
    "\n",
    "var=var[::-1]\n",
    "print (\"var after reverse --> \", var)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 80,
   "id": "eb577f36-ac5b-4848-bc6e-b297150e6899",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "s1 -->  True\n",
      "s2 -->  False\n"
     ]
    }
   ],
   "source": [
    "s1=\"malayalam\"\n",
    "s2=\"teacher\"\n",
    "print (\"s1 --> \", s1==s1[::-1])\n",
    "print (\"s2 --> \", s2==s2[::-1])"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "35c734a2-8822-455e-804a-ce75068573b9",
   "metadata": {},
   "source": [
    "## Random Numbers/String"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 96,
   "id": "1416cb9f-eaa8-4eb4-a534-1445c5c4ad3b",
   "metadata": {},
   "outputs": [],
   "source": [
    "import random as r\n",
    "import string as s"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 86,
   "id": "f0a62319-6947-4961-9da1-b4dbe832117f",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "0.428645678469767\n",
      "0.40775482481299485\n",
      "0.866561\n"
     ]
    }
   ],
   "source": [
    "print(r.random())\n",
    "print(r.random())\n",
    "print(round(r.random(),6))"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 88,
   "id": "66e4d99d-0d3d-4920-b3fa-bff6bb5c5b6c",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "75\n",
      "770\n",
      "-2\n",
      "2\n"
     ]
    }
   ],
   "source": [
    "print (r.randint(1, 100))\n",
    "print (r.randint(1, 1000))\n",
    "print (r.randint(-10, 100))\n",
    "print (r.randint(-10, 10))"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 93,
   "id": "535d67bf-8053-44f6-8454-c7ed67397948",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "17.526271484460622\n",
      "57.15608314631678\n",
      "6.570674990286275\n",
      "-1.1597495082607416\n",
      "-4.7\n"
     ]
    }
   ],
   "source": [
    "print (r.uniform(1, 100))\n",
    "print (r.uniform(1, 1000))\n",
    "print (r.uniform (-10, 10))\n",
    "print (r.uniform (-10, 10))\n",
    "print (round(r.uniform (-10, 10),1))"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 95,
   "id": "8b759437-118a-47ad-97e4-e514b922813c",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "[8, 3, 1, 4]\n",
      "[10, 8]\n",
      "[20, 64, 11]\n",
      "[-82, -38, -98, -76, -11]\n"
     ]
    }
   ],
   "source": [
    "A=[1, 2, 3, 4, 5, 6, 7, 8, 9, 10]\n",
    "\n",
    "print (r.sample(A, 4))\n",
    "print (r.sample(A, 2))\n",
    "print (r.sample(range(0,100), 3))\n",
    "print (r.sample(range(-100,100), 5))"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 98,
   "id": "4a1bc181-947b-4b2c-b698-dc86cca67e6b",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "String        -->  abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ\n",
      "Selected Char -->  ['f', 'L', 'R', 'w', 'S', 'd', 'U', 'T']\n",
      "passwd1       -->  fLRwSdUT\n",
      "passwd2       -->  f+L+R+w+S+d+U+T\n",
      "passwd3       -->  f*L*R*w*S*d*U*T\n"
     ]
    }
   ],
   "source": [
    "print (\"String        --> \",s.ascii_letters)\n",
    "\n",
    "passwd=r.sample(s.ascii_letters, 8)\n",
    "print (\"Selected Char --> \",passwd)\n",
    "\n",
    "passwd1=\"\".join(passwd)\n",
    "print (\"passwd1       --> \",passwd1)\n",
    "\n",
    "passwd2=\"+\".join(passwd)\n",
    "print (\"passwd2       --> \",passwd2)\n",
    "\n",
    "passwd3=\"*\".join(passwd)\n",
    "print (\"passwd3       --> \",passwd3)\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 99,
   "id": "b194c249-8be6-41b0-bb74-9b8bef8eb689",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Digits -->  0123456789\n",
      "Selected num1 -->  ['2', '5', '1', '0', '3']\n",
      "otp1          -->  25103\n",
      "Selected num2 -->  ['7', '6', '8', '3', '9']\n",
      "otp2          -->  76839\n",
      "Selected num2 -->  ['5', '2', '7', '9', '6']\n",
      "otp3          -->  52796\n"
     ]
    }
   ],
   "source": [
    "print (\"Digits --> \",s.digits)\n",
    "\n",
    "otp=r.sample(s.digits, 5)\n",
    "print (\"Selected num1 --> \",otp)\n",
    "otp=\"\".join(otp)\n",
    "print (\"otp1          --> \",otp)\n",
    "\n",
    "otp=r.sample(s.digits, 5)\n",
    "print (\"Selected num2 --> \",otp)\n",
    "otp=\"\".join(otp)\n",
    "print (\"otp2          --> \",otp)\n",
    "\n",
    "otp=r.sample(s.digits, 5)\n",
    "print (\"Selected num2 --> \",otp)\n",
    "otp=\"\".join(otp)\n",
    "print (\"otp3          --> \",otp)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 100,
   "id": "42e32f1c-ac89-4741-8aa1-3d86b09e374e",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "String + Digits -->  abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789\n",
      "\n",
      "Selected Str1 -->  ['6', 'm', 'W', 's', 'c', '8']\n",
      "mixPasswd1    -->  6mWsc8\n",
      "\n",
      "Selected Str2 -->  ['H', '0', 'b', 'i', 'Q', 'S', 'y', 't']\n",
      "mixPasswd2    -->  H0biQSyt\n",
      "\n",
      "Selected Str3 -->  ['L', '[', 'k', 'd', 'a', '4', '(', 'W']\n",
      "mixPasswd3    -->  L[kda4(W\n"
     ]
    }
   ],
   "source": [
    "print (\"String + Digits --> \",s.ascii_letters + s.digits)\n",
    "\n",
    "mixPasswd=r.sample(s.ascii_letters + s.digits, 6)\n",
    "print (\"\\nSelected Str1 --> \",mixPasswd)\n",
    "mixPasswd=\"\".join(mixPasswd)\n",
    "print (\"mixPasswd1    --> \",mixPasswd)\n",
    "\n",
    "mixPasswd=r.sample(s.ascii_letters + s.digits, 8)\n",
    "print (\"\\nSelected Str2 --> \",mixPasswd)\n",
    "mixPasswd=\"\".join(mixPasswd)\n",
    "print (\"mixPasswd2    --> \",mixPasswd)\n",
    "\n",
    "splChar=\"#@!~%^&*()_+=-[]{}|\"\n",
    "mixPasswd=r.sample(splChar + s.ascii_letters + s.digits, 8)\n",
    "print (\"\\nSelected Str3 --> \",mixPasswd)\n",
    "mixPasswd=\"\".join(mixPasswd)\n",
    "print (\"mixPasswd3    --> \",mixPasswd)"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "f1072ed0-2993-4c2e-a387-c71421795487",
   "metadata": {},
   "source": [
    "## Exception Handling"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 102,
   "id": "008b17e4-cbec-41bd-9569-8c579e0ce1a4",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "100/ -6 --> -16.666666666666668\n",
      "100/ -5 --> -20.0\n",
      "100/ -4 --> -25.0\n",
      "100/ -3 --> -33.333333333333336\n",
      "100/ -2 --> -50.0\n",
      "100/ -1 --> -100.0\n"
     ]
    },
    {
     "ename": "ZeroDivisionError",
     "evalue": "division by zero",
     "output_type": "error",
     "traceback": [
      "\u001b[31m---------------------------------------------------------------------------\u001b[39m",
      "\u001b[31mZeroDivisionError\u001b[39m                         Traceback (most recent call last)",
      "\u001b[36mCell\u001b[39m\u001b[36m \u001b[39m\u001b[32mIn[102]\u001b[39m\u001b[32m, line 2\u001b[39m\n\u001b[32m      1\u001b[39m \u001b[38;5;28;01mfor\u001b[39;00m i \u001b[38;5;129;01min\u001b[39;00m \u001b[38;5;28mrange\u001b[39m(-\u001b[32m6\u001b[39m,\u001b[32m8\u001b[39m):\n\u001b[32m----> \u001b[39m\u001b[32m2\u001b[39m     \u001b[38;5;28mprint\u001b[39m(\u001b[33m\"\u001b[39m\u001b[33m100/\u001b[39m\u001b[33m\"\u001b[39m,i,\u001b[33m\"\u001b[39m\u001b[33m-->\u001b[39m\u001b[33m\"\u001b[39m,\u001b[32;43m100\u001b[39;49m\u001b[43m/\u001b[49m\u001b[43mi\u001b[49m)\n",
      "\u001b[31mZeroDivisionError\u001b[39m: division by zero"
     ]
    }
   ],
   "source": [
    "for i in range(-6,8):\n",
    "    print(\"100/\",i,\"-->\",100/i)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 103,
   "id": "40906b30-cd84-46f5-9059-f69c06c299e1",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "100/ -6 --> -16.666666666666668\n",
      "100/ -5 --> -20.0\n",
      "100/ -4 --> -25.0\n",
      "100/ -3 --> -33.333333333333336\n",
      "100/ -2 --> -50.0\n",
      "100/ -1 --> -100.0\n",
      "error\n",
      "100/ 1 --> 100.0\n",
      "100/ 2 --> 50.0\n",
      "100/ 3 --> 33.333333333333336\n",
      "100/ 4 --> 25.0\n",
      "100/ 5 --> 20.0\n",
      "100/ 6 --> 16.666666666666668\n",
      "100/ 7 --> 14.285714285714286\n"
     ]
    }
   ],
   "source": [
    "for i in range(-6,8):\n",
    "    try:\n",
    "        print(\"100/\",i,\"-->\",100/i)\n",
    "    except:\n",
    "        print(\"error\")"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 105,
   "id": "ba4d8738-74a2-4256-8cfd-5b2bff65ed95",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "0 --> 1\n",
      "1 --> 2\n",
      "2 --> 3\n",
      "3 --> 4\n",
      "4 --> 5\n",
      "error\n",
      "error\n",
      "error\n"
     ]
    }
   ],
   "source": [
    "l=[1,2,3,4,5]\n",
    "for i in range(8):\n",
    "    try:\n",
    "        print(i,\"-->\",l[i])\n",
    "    except:\n",
    "        print(\"error\")"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 107,
   "id": "06dfbd22-b45e-4287-a6d8-f1f0c9205e7a",
   "metadata": {},
   "outputs": [
    {
     "name": "stdin",
     "output_type": "stream",
     "text": [
      "enter file name:  image.txt\n"
     ]
    },
    {
     "ename": "FileNotFoundError",
     "evalue": "[Errno 2] No such file or directory: 'image.txt'",
     "output_type": "error",
     "traceback": [
      "\u001b[31m---------------------------------------------------------------------------\u001b[39m",
      "\u001b[31mFileNotFoundError\u001b[39m                         Traceback (most recent call last)",
      "\u001b[36mCell\u001b[39m\u001b[36m \u001b[39m\u001b[32mIn[107]\u001b[39m\u001b[32m, line 2\u001b[39m\n\u001b[32m      1\u001b[39m fileName=\u001b[38;5;28minput\u001b[39m(\u001b[33m\"\u001b[39m\u001b[33menter file name: \u001b[39m\u001b[33m\"\u001b[39m)\n\u001b[32m----> \u001b[39m\u001b[32m2\u001b[39m fp=\u001b[38;5;28;43mopen\u001b[39;49m\u001b[43m(\u001b[49m\u001b[43mfileName\u001b[49m\u001b[43m)\u001b[49m\n\u001b[32m      3\u001b[39m fp.close()\n\u001b[32m      4\u001b[39m \u001b[38;5;28mprint\u001b[39m(\u001b[33m\"\u001b[39m\u001b[33mDone\u001b[39m\u001b[33m\"\u001b[39m)\n",
      "\u001b[36mFile \u001b[39m\u001b[32m~\\anaconda3\\Lib\\site-packages\\IPython\\core\\interactiveshell.py:343\u001b[39m, in \u001b[36m_modified_open\u001b[39m\u001b[34m(file, *args, **kwargs)\u001b[39m\n\u001b[32m    336\u001b[39m \u001b[38;5;28;01mif\u001b[39;00m file \u001b[38;5;129;01min\u001b[39;00m {\u001b[32m0\u001b[39m, \u001b[32m1\u001b[39m, \u001b[32m2\u001b[39m}:\n\u001b[32m    337\u001b[39m     \u001b[38;5;28;01mraise\u001b[39;00m \u001b[38;5;167;01mValueError\u001b[39;00m(\n\u001b[32m    338\u001b[39m         \u001b[33mf\u001b[39m\u001b[33m\"\u001b[39m\u001b[33mIPython won\u001b[39m\u001b[33m'\u001b[39m\u001b[33mt let you open fd=\u001b[39m\u001b[38;5;132;01m{\u001b[39;00mfile\u001b[38;5;132;01m}\u001b[39;00m\u001b[33m by default \u001b[39m\u001b[33m\"\u001b[39m\n\u001b[32m    339\u001b[39m         \u001b[33m\"\u001b[39m\u001b[33mas it is likely to crash IPython. If you know what you are doing, \u001b[39m\u001b[33m\"\u001b[39m\n\u001b[32m    340\u001b[39m         \u001b[33m\"\u001b[39m\u001b[33myou can use builtins\u001b[39m\u001b[33m'\u001b[39m\u001b[33m open.\u001b[39m\u001b[33m\"\u001b[39m\n\u001b[32m    341\u001b[39m     )\n\u001b[32m--> \u001b[39m\u001b[32m343\u001b[39m \u001b[38;5;28;01mreturn\u001b[39;00m \u001b[43mio_open\u001b[49m\u001b[43m(\u001b[49m\u001b[43mfile\u001b[49m\u001b[43m,\u001b[49m\u001b[43m \u001b[49m\u001b[43m*\u001b[49m\u001b[43margs\u001b[49m\u001b[43m,\u001b[49m\u001b[43m \u001b[49m\u001b[43m*\u001b[49m\u001b[43m*\u001b[49m\u001b[43mkwargs\u001b[49m\u001b[43m)\u001b[49m\n",
      "\u001b[31mFileNotFoundError\u001b[39m: [Errno 2] No such file or directory: 'image.txt'"
     ]
    }
   ],
   "source": [
    "fileName=input(\"enter file name: \")\n",
    "fp=open(fileName)\n",
    "fp.close()\n",
    "print(\"Done\")"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 110,
   "id": "fb24154a-37ae-49d1-81a0-c3a56ebabef2",
   "metadata": {},
   "outputs": [
    {
     "name": "stdin",
     "output_type": "stream",
     "text": [
      "enter file name:  image.txt\n"
     ]
    },
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "error! \"image.txt\" File Not Found\n",
      "done\n"
     ]
    }
   ],
   "source": [
    "fileName=input(\"enter file name: \")\n",
    "try:\n",
    "    fp=open(fileName)\n",
    "    fp.close()\n",
    "except:\n",
    "    print(\"error! \\\"%s\\\" File Not Found\"%(fileName))\n",
    "\n",
    "print(\"done\")"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "594e6616-3bc8-4ae2-871e-a8d9c5aed2f1",
   "metadata": {},
   "source": [
    "## List"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 112,
   "id": "ba392af3-add3-4517-83ea-8dbaced85871",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "original list:  ['Riya', 'Sharma', 10.5, 5]\n",
      "number of elements in list:  4\n"
     ]
    }
   ],
   "source": [
    "l=[\"Riya\",\"Sharma\",10.5,5]\n",
    "print(\"original list: \",l)\n",
    "print(\"number of elements in list: \",len(l))   "
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 113,
   "id": "fa821095-0ca1-439e-bb3a-28435b884e85",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "original list:  ['Riya', 'Sharma', 10.5, 5]\n",
      "Riya\n",
      "Sharma\n",
      "10.5\n",
      "5\n"
     ]
    }
   ],
   "source": [
    "l=[\"Riya\",\"Sharma\",10.5,5]\n",
    "print(\"original list: \",l)\n",
    "i=0\n",
    "while i<len(l):\n",
    "    print(l[i])\n",
    "    i+=1"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 115,
   "id": "63b69d98-1bfe-45fc-bd4e-06b706b5cc1a",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "original list:  ['Riya', 'Sharma', 10.5, 5]\n",
      "Riya\n",
      "Sharma\n",
      "10.5\n",
      "5\n"
     ]
    }
   ],
   "source": [
    "l=[\"Riya\",\"Sharma\",10.5,5]\n",
    "print(\"original list: \",l)\n",
    "for i in range(0,len(l)):\n",
    "    print(l[i])"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 116,
   "id": "88037c52-6e5b-498e-addc-f5181a1c3500",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "original list:  ['Riya', 'Sharma', 10.5, 5]\n",
      "Riya\n",
      "Sharma\n",
      "10.5\n",
      "5\n"
     ]
    }
   ],
   "source": [
    "l=[\"Riya\",\"Sharma\",10.5,5]\n",
    "print(\"original list: \",l)\n",
    "for s in l:\n",
    "    print(s)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 117,
   "id": "76d4a1f1-72a8-46c3-9948-197ede5a79ec",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "original list:  ['Riya', 'Sharma', 10.5, 5]\n",
      "list after adding:  ['Riya', 'Sharma', 10.5, 5, 'Rishab']\n",
      "list after deleting:  ['Riya', 10.5, 5, 'Rishab']\n"
     ]
    }
   ],
   "source": [
    "l=[\"Riya\",\"Sharma\",10.5,5]\n",
    "print(\"original list: \",l)\n",
    "\n",
    "l.append(\"Rishab\")\n",
    "print(\"list after adding: \",l)\n",
    "\n",
    "del l[1]\n",
    "print(\"list after deleting: \",l)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 119,
   "id": "478820ab-e02e-4b3c-84c2-7f5df3e0aaae",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "original list:  [2, 4, 6, 14, 8, 11]\n",
      "Sum     -->  45\n",
      "Average -->  7.5\n",
      "Average -->  7\n",
      "L * 3   -->  [2, 4, 6, 14, 8, 11, 2, 4, 6, 14, 8, 11, 2, 4, 6, 14, 8, 11, 2, 4, 6, 14, 8, 11]\n",
      "L + L   -->  [2, 4, 6, 14, 8, 11, 2, 4, 6, 14, 8, 11]\n"
     ]
    }
   ],
   "source": [
    "L=[2,4,6,14,8,11]\n",
    "print(\"original list: \",L)\n",
    "\n",
    "print (\"Sum     --> \", sum(L))\n",
    "print (\"Average --> \", sum(L)/len(L))\n",
    "print (\"Average --> \", sum(L)//len(L))\n",
    "\n",
    "print (\"L * 3   --> \", L * 4)     \n",
    "print (\"L + L   --> \", L + L)   \n",
    "     "
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 120,
   "id": "2968d7a2-8598-49e2-92ec-6bada21c3cb2",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "original list:  [2, 4, 6, 14, 8, 11]\n",
      "max -->  14\n",
      "min -->  2\n",
      "\n",
      "Before Sort            -->  [2, 4, 6, 14, 8, 11]\n",
      "After Sort (Asending)  -->  [2, 4, 6, 8, 11, 14]\n",
      "After Sort (Desending) -->  [14, 11, 8, 6, 4, 2]\n"
     ]
    }
   ],
   "source": [
    "L=[2,4,6,14,8,11]\n",
    "print(\"original list: \",L)\n",
    "\n",
    "print (\"max --> \", max(L))\n",
    "print (\"min --> \", min(L))\n",
    "\n",
    "print (\"\\nBefore Sort            --> \", L)\n",
    "L.sort()\n",
    "\n",
    "print (\"After Sort (Asending)  --> \", L)\n",
    "\n",
    "L.sort(reverse=True)\n",
    "print (\"After Sort (Desending) --> \", L)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 121,
   "id": "a6580d38-9a7d-49f6-9e36-39fc67956ea4",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "L1 -->  [2, 4, 6]\n",
      "L2 -->  [16, 8, 5, 6]\n",
      "L3 -->  [2, 4, 6, 16, 8, 5, 6]\n",
      "\n",
      "L3[2:]  -->  [6, 16, 8, 5, 6]\n",
      "L3[2:5] -->  [6, 16, 8]\n",
      "L3[:-1] -->  [2, 4, 6, 16, 8, 5]\n",
      "L3[::2] -->  [2, 6, 8, 6]\n"
     ]
    }
   ],
   "source": [
    "L1=[2,4,6]\n",
    "L2=[16,8,5,6]\n",
    "L3=L1+L2\n",
    "\n",
    "print (\"L1 --> \",L1)\n",
    "print (\"L2 --> \",L2)\n",
    "print (\"L3 --> \",L3)\n",
    "\n",
    "print (\"\\nL3[2:]  --> \",L3[2:])\n",
    "print (\"L3[2:5] --> \",L3[2:5])\n",
    "print (\"L3[:-1] --> \",L3[:-1])\n",
    "print (\"L3[::2] --> \",L3[::2])"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 122,
   "id": "d66d5884-3e79-4c8a-8936-035ee553ed5c",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "original list:  [2, 4, 6, 14, 8, 11]\n",
      "After multiplying with constant:  [12, 24, 36, 84, 48, 66]\n"
     ]
    }
   ],
   "source": [
    "L=[2,4,6,14,8,11]\n",
    "print(\"original list: \",L)\n",
    "\n",
    "newL=[i*6 for i in L]\n",
    "print(\"After multiplying with constant: \",newL)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 124,
   "id": "47cd92d2-40e8-46de-b3eb-ffb9573e3ca5",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Original List -->  True\n",
      "Original List -->  False\n",
      "Original List -->  True\n",
      "Present\n",
      "Present\n"
     ]
    }
   ],
   "source": [
    "L=[2,4,6,14,8,11]\n",
    "print (\"Original List --> \", 4 in L)\n",
    "print (\"Original List --> \", 15 in L)\n",
    "print (\"Original List --> \", 11 in L)\n",
    "\n",
    "if (4 in L) == True:\n",
    "\tprint (\"Present\")\n",
    "else:\n",
    "\tprint (\"Not Present\")\n",
    "\n",
    "if 11 in L == False:\n",
    "\tprint (\"Not Present\")\n",
    "else:\n",
    "\tprint (\"Present\")"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "3b42005c-3441-4df9-a422-1e8fa60d1b8c",
   "metadata": {},
   "source": [
    "## Dictionary"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 126,
   "id": "de850d73-0f08-4ad2-a775-b9f444d4323e",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Dictionary      -->  {1: 8.9, 2: 5.6, 4: 6.7, 7: 9.1, 8: 5.3}\n",
      "Num of elements -->  5\n",
      "CGPA of 1       -->  8.9\n",
      "CGPA of 4       -->  6.7\n",
      "CGPA of 7       -->  9.1\n"
     ]
    },
    {
     "ename": "KeyError",
     "evalue": "3",
     "output_type": "error",
     "traceback": [
      "\u001b[31m---------------------------------------------------------------------------\u001b[39m",
      "\u001b[31mKeyError\u001b[39m                                  Traceback (most recent call last)",
      "\u001b[36mCell\u001b[39m\u001b[36m \u001b[39m\u001b[32mIn[126]\u001b[39m\u001b[32m, line 8\u001b[39m\n\u001b[32m      6\u001b[39m \u001b[38;5;28mprint\u001b[39m (\u001b[33m\"\u001b[39m\u001b[33mCGPA of 4       --> \u001b[39m\u001b[33m\"\u001b[39m, CGPA[\u001b[32m4\u001b[39m])\n\u001b[32m      7\u001b[39m \u001b[38;5;28mprint\u001b[39m (\u001b[33m\"\u001b[39m\u001b[33mCGPA of 7       --> \u001b[39m\u001b[33m\"\u001b[39m, CGPA[\u001b[32m7\u001b[39m])\n\u001b[32m----> \u001b[39m\u001b[32m8\u001b[39m \u001b[38;5;28mprint\u001b[39m (\u001b[33m\"\u001b[39m\u001b[33mCGPA of 3       --> \u001b[39m\u001b[33m\"\u001b[39m, \u001b[43mCGPA\u001b[49m\u001b[43m[\u001b[49m\u001b[32;43m3\u001b[39;49m\u001b[43m]\u001b[49m)\n",
      "\u001b[31mKeyError\u001b[39m: 3"
     ]
    }
   ],
   "source": [
    "CGPA={1:8.9, 2:5.6, 4:6.7, 7:9.1, 8:5.3}\n",
    "print (\"Dictionary      --> \", CGPA)\n",
    "print (\"Num of elements --> \", len(CGPA))\n",
    "\n",
    "print (\"CGPA of 1       --> \", CGPA[1])\n",
    "print (\"CGPA of 4       --> \", CGPA[4])\n",
    "print (\"CGPA of 7       --> \", CGPA[7])\n",
    "print (\"CGPA of 3       --> \", CGPA[3])"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 127,
   "id": "6ccd50c6-21d1-453e-810d-7ecb20101ff5",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "CGPA of  1  -->  8.9\n",
      "CGPA of  2  -->  5.6\n",
      "CGPA of  4  -->  6.7\n",
      "CGPA of  7  -->  9.1\n",
      "CGPA of  8  -->  5.3\n"
     ]
    }
   ],
   "source": [
    "CGPA={1:8.9, 2:5.6, 4:6.7, 7:9.1, 8:5.3}\n",
    "for k in CGPA:\n",
    "\tprint (\"CGPA of \", k, \" --> \", CGPA[k])"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 128,
   "id": "6b60ee9c-885b-4f2a-a447-0fe0fd92e458",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Dictionary -->  {1: 8.9, 2: 5.6, 4: 6.7, 7: 9.1, 8: 5.3}\n",
      "Keys       -->  [1, 2, 4, 7, 8]\n",
      "Values     -->  [8.9, 5.6, 6.7, 9.1, 5.3]\n"
     ]
    }
   ],
   "source": [
    "CGPA={1:8.9, 2:5.6, 4:6.7, 7:9.1, 8:5.3}\n",
    "print (\"Dictionary --> \", CGPA)\n",
    "print (\"Keys       --> \", list(CGPA.keys()))\n",
    "print (\"Values     --> \", list(CGPA.values()))"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 129,
   "id": "25471c01-3a86-495d-b302-2efad3216810",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Original Dictionary -->  {1: 8.9, 2: 5.6, 4: 6.7, 7: 9.1, 8: 5.3}\n",
      "After Updating (4)  -->  {1: 8.9, 2: 5.6, 4: 9.2, 7: 9.1, 8: 5.3}\n",
      "After Adding (3)    -->  {1: 8.9, 2: 5.6, 4: 9.2, 7: 9.1, 8: 5.3, 3: 8.6}\n",
      "After Deleting (1)  -->  {2: 5.6, 4: 9.2, 7: 9.1, 8: 5.3, 3: 8.6}\n",
      "After Clear         -->  {}\n"
     ]
    },
    {
     "ename": "NameError",
     "evalue": "name 'CGPA' is not defined",
     "output_type": "error",
     "traceback": [
      "\u001b[31m---------------------------------------------------------------------------\u001b[39m",
      "\u001b[31mNameError\u001b[39m                                 Traceback (most recent call last)",
      "\u001b[36mCell\u001b[39m\u001b[36m \u001b[39m\u001b[32mIn[129]\u001b[39m\u001b[32m, line 17\u001b[39m\n\u001b[32m     14\u001b[39m \u001b[38;5;28mprint\u001b[39m (\u001b[33m\"\u001b[39m\u001b[33mAfter Clear         --> \u001b[39m\u001b[33m\"\u001b[39m, CGPA)\n\u001b[32m     16\u001b[39m \u001b[38;5;28;01mdel\u001b[39;00m CGPA\n\u001b[32m---> \u001b[39m\u001b[32m17\u001b[39m \u001b[38;5;28mprint\u001b[39m (\u001b[33m\"\u001b[39m\u001b[33mAfter Delete        --> \u001b[39m\u001b[33m\"\u001b[39m, \u001b[43mCGPA\u001b[49m)\n",
      "\u001b[31mNameError\u001b[39m: name 'CGPA' is not defined"
     ]
    }
   ],
   "source": [
    "CGPA={1:8.9,2:5.6,4:6.7,7:9.1,8:5.3}\n",
    "print (\"Original Dictionary --> \", CGPA)\n",
    "\n",
    "CGPA[4] = 9.2\n",
    "print (\"After Updating (4)  --> \", CGPA)\n",
    "\n",
    "CGPA[3] = 8.6\n",
    "print (\"After Adding (3)    --> \", CGPA)\n",
    "\n",
    "del CGPA[1]\n",
    "print (\"After Deleting (1)  --> \", CGPA)\n",
    "\n",
    "CGPA.clear()\n",
    "print (\"After Clear         --> \", CGPA)\n",
    "\n",
    "del CGPA\n",
    "print (\"After Delete        --> \", CGPA)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 130,
   "id": "5046e9c5-61db-4e3f-b3a8-402e8589c34d",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Original Dictionary -->  {1: 8.9, 2: 5.6, 4: 6.7, 7: 9.1, 8: 5.3}\n",
      "Is Key 2 Present    -->  True\n",
      "Is Key 9 Present    -->  False\n"
     ]
    }
   ],
   "source": [
    "CGPA={1:8.9, 2:5.6, 4:6.7, 7:9.1, 8:5.3}\n",
    "print (\"Original Dictionary --> \", CGPA)\n",
    "print (\"Is Key 2 Present    --> \", 2 in CGPA)\n",
    "print (\"Is Key 9 Present    --> \", 9 in CGPA)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 131,
   "id": "1d6e2739-40d3-4422-834c-ef2a92e8c2f3",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Original Dictionary -->  {'Rahul': 'Delhi', 'Gobind': 'Gwalior', 'Anil': 'Mohali', 'Pankaj': 'Noida'}\n",
      "Home Town of Prashant is -->  Delhi\n",
      "Home Town of Govind is   -->  Gwalior\n",
      "Home Town of Anil is     -->  Mohali\n",
      "Home Town of Pankaj is   -->  Noida\n"
     ]
    }
   ],
   "source": [
    "HomeTown={\"Rahul\":\"Delhi\", \"Gobind\":\"Gwalior\", \"Anil\":\"Mohali\", \"Pankaj\":\"Noida\"}\n",
    "print (\"Original Dictionary --> \", HomeTown)\n",
    "print (\"Home Town of Prashant is --> \", HomeTown[\"Rahul\"])\n",
    "print (\"Home Town of Govind is   --> \", HomeTown[\"Gobind\"])\n",
    "print (\"Home Town of Anil is     --> \", HomeTown[\"Anil\"])\n",
    "print (\"Home Town of Pankaj is   --> \", HomeTown[\"Pankaj\"])"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 132,
   "id": "8bf398c2-20a5-4bce-af57-b752427de6ca",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Original Dictionary -->  {'Rahul': 'Delhi', 'Gobind': 'Gwalior', 'Anil': 'Mohali', 'Pankaj': 'Noida'}\n",
      "Home Town of  Rahul  is  -->  Delhi\n",
      "Home Town of  Gobind  is  -->  Gwalior\n",
      "Home Town of  Anil  is  -->  Mohali\n",
      "Home Town of  Pankaj  is  -->  Noida\n"
     ]
    }
   ],
   "source": [
    "HomeTown={\"Rahul\":\"Delhi\", \"Gobind\":\"Gwalior\", \"Anil\":\"Mohali\", \"Pankaj\":\"Noida\"}\n",
    "print (\"Original Dictionary --> \", HomeTown)\n",
    "for d in HomeTown:\n",
    "\tprint (\"Home Town of \", d, \" is  --> \", HomeTown[d])"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "c121ba8d-c385-4f2c-8ff0-f33774a41e17",
   "metadata": {},
   "source": [
    "## Tuple"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 134,
   "id": "a65c6e11-27b5-46a8-8202-4d34813d4185",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "T --> ('Riya', 'Sharma', 10.5, 5)\n",
      "Number of elements:  4\n",
      "Type of Object:  <class 'tuple'>\n"
     ]
    }
   ],
   "source": [
    "T=(\"Riya\",\"Sharma\",10.5,5)\n",
    "print(\"T -->\",T)\n",
    "print(\"Number of elements: \",len(T))\n",
    "print(\"Type of Object: \",type(T))"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 135,
   "id": "ed91ebda-908b-4e13-9569-fbf3e9a8d79e",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "T --> ('Riya', 'Sharma', 10.5, 5)\n",
      "Number of elements:  4\n",
      "Type of Object:  <class 'tuple'>\n"
     ]
    }
   ],
   "source": [
    "T=tuple((\"Riya\",\"Sharma\",10.5,5))\n",
    "print(\"T -->\",T)\n",
    "print(\"Number of elements: \",len(T))\n",
    "print(\"Type of Object: \",type(T))"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 137,
   "id": "33384719-dd74-4b75-ba13-140466949f50",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "T --> ('Riya', 'Sharma', 10.5, 5)\n",
      "Riya\n",
      "Sharma\n",
      "10.5\n",
      "5\n"
     ]
    }
   ],
   "source": [
    "T=(\"Riya\",\"Sharma\",10.5,5)\n",
    "print(\"T -->\",T)\n",
    "i=0\n",
    "while i<len(T):\n",
    "    print(T[i])\n",
    "    i+=1"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 138,
   "id": "9b5941ea-0bc5-485c-9ef0-410bae79161c",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "T --> ('Riya', 'Sharma', 10.5, 5)\n",
      "Riya\n",
      "Sharma\n",
      "10.5\n",
      "5\n"
     ]
    }
   ],
   "source": [
    "T=(\"Riya\",\"Sharma\",10.5,5)\n",
    "print(\"T -->\",T)\n",
    "for i in range(0,len(T)):\n",
    "    print(T[i])"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 139,
   "id": "29f2a297-2b5d-444f-9781-39e2f75cd326",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "T --> ('Riya', 'Sharma', 10.5, 5)\n",
      "Riya\n",
      "Sharma\n",
      "10.5\n",
      "5\n"
     ]
    }
   ],
   "source": [
    "T=(\"Riya\",\"Sharma\",10.5,5)\n",
    "print(\"T -->\",T)\n",
    "for s in T:\n",
    "    print(s)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 142,
   "id": "3f08f1b9-7e4f-4c24-9bd1-8f522acb9dc4",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "T     --> (2, 4, 6, 15, 8, 9, 1)\n",
      "T[1]  --> 4\n",
      "T[2]  --> 6\n",
      "T[-1] --> 1\n",
      "T[-2] --> 9\n"
     ]
    }
   ],
   "source": [
    "T = (2,4,6,15,8,9,1)\n",
    "print (\"T     -->\", T)\n",
    "\n",
    "print (\"T[1]  -->\", T[1])\n",
    "print (\"T[2]  -->\", T[2])\n",
    "print (\"T[-1] -->\", T[-1])\n",
    "print (\"T[-2] -->\", T[-2])"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 143,
   "id": "df82d356-2755-4b7c-80a5-fa1230311505",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "T     --> (2, 4, 6, 15, 8, 9, 1)\n",
      "T[1:3]   --> (4, 6)\n",
      "T[2:]    --> (6, 15, 8, 9, 1)\n",
      "T[2:5]   --> (6, 15, 8)\n",
      "T[:2]    --> (2, 4)\n",
      "T[:-1]   --> (2, 4, 6, 15, 8, 9)\n",
      "T[-4:-1] --> (15, 8, 9)\n"
     ]
    }
   ],
   "source": [
    "T = (2,4,6,15,8,9,1)\n",
    "print (\"T     -->\", T)\n",
    "\n",
    "print (\"T[1:3]   -->\", T[1:3])\n",
    "print (\"T[2:]    -->\", T[2:])\n",
    "print (\"T[2:5]   -->\", T[2:5])\n",
    "print (\"T[:2]    -->\", T[:2])\n",
    "print (\"T[:-1]   -->\", T[:-1])\n",
    "print (\"T[-4:-1] -->\", T[-4:-1])\n",
    "     "
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 144,
   "id": "e4e05f41-0cf2-4844-a09e-12f5eaf5726e",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "T     --> (2, 4, 6, 15, 8, 9, 1)\n",
      "T       --> (2, 4, 6, 15, 8, 9, 1)\n",
      "Sum     --> 45\n",
      "Average --> 6.428571428571429\n",
      "Average --> 6\n"
     ]
    }
   ],
   "source": [
    "T = (2,4,6,15,8,9,1)\n",
    "print (\"T     -->\", T)\n",
    "\n",
    "print (\"T       -->\", T)\n",
    "print (\"Sum     -->\", sum(T))\n",
    "print (\"Average -->\", sum(T)/len(T))\n",
    "print (\"Average -->\", sum(T)//len(T))"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 145,
   "id": "f3c37b3c-557f-4e30-921c-041c902d7bda",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "T     --> (2, 4, 6, 15, 8, 9, 1)\n",
      "Max --> 15\n",
      "Min --> 1\n"
     ]
    }
   ],
   "source": [
    "T = (2,4,6,15,8,9,1)\n",
    "print (\"T     -->\", T)\n",
    "print (\"Max -->\", max(T))\n",
    "print (\"Min -->\", min(T))"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 147,
   "id": "d6f5648a-8c10-4000-bdbf-c72c79f86d70",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "T   --> ('Ram', 'Shyam', 'Human', 'Ant')\n",
      "Max --> Shyam\n",
      "Min --> Ant\n"
     ]
    }
   ],
   "source": [
    "T = (\"Ram\", \"Shyam\", \"Human\", \"Ant\")    \n",
    "print (\"T   -->\", T)\n",
    "print (\"Max -->\", max(T))\n",
    "print (\"Min -->\", min(T))"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 148,
   "id": "60437fb1-3e1d-4fcd-81f1-88f1e5b9be66",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "T1 --> (4, 8, 12)\n",
      "T2 --> (11, 6, 8, 2)\n",
      "T3 --> (4, 8, 12, 11, 6, 8, 2)\n",
      "T4 --> (4, 8, 12, 11, 6, 8, 2, 4, 8, 12, 11, 6, 8, 2)\n"
     ]
    }
   ],
   "source": [
    "T1 = (4,8,12)\n",
    "T2 = (11,6,8,2)\n",
    "\n",
    "print (\"T1 -->\", T1)\n",
    "print (\"T2 -->\", T2)\n",
    "\n",
    "T3 = T1 + T2\n",
    "print (\"T3 -->\", T3)\n",
    "\n",
    "T4 = T1 + T2 + T1 + T2\n",
    "print (\"T4 -->\", T4)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 149,
   "id": "2292fdcf-c6e2-4852-9990-22d589bb3ef3",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "T1 --> (4, 8, 12)\n",
      "T2 --> (11, 6, 8, 2)\n",
      "T3 --> (8, 6, 8)\n",
      "T4 --> (4, 11)\n"
     ]
    }
   ],
   "source": [
    "T1 = (4,8,12)\n",
    "T2 = (11,6,8,2)\n",
    "\n",
    "print (\"T1 -->\", T1)\n",
    "print (\"T2 -->\", T2)\n",
    "\n",
    "T3 = T1[1:2] + T2[1:3]\n",
    "print (\"T3 -->\", T3)\n",
    "\n",
    "T4 = T1[:-2] + T2[:-3]\n",
    "print (\"T4 -->\", T4)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 151,
   "id": "174ff51e-eb14-4828-8c1a-005e822a3214",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "T --> (2, 4, 6, 15, 8, 9, 1)\n",
      "6  in T --> True\n",
      "10 in T --> False\n",
      "15 in T --> True\n"
     ]
    }
   ],
   "source": [
    "T = (2,4,6,15,8,9,1)\n",
    "print(\"T -->\",T)\n",
    "\n",
    "print (\"6  in T -->\", 6 in T)\n",
    "print (\"10 in T -->\", 10 in T)\n",
    "print (\"15 in T -->\", 15 in T)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 152,
   "id": "33992d68-9904-4b38-898b-9bc8d5a67289",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "T --> ('Riya', 'Sharma', 10.5, 5)\n"
     ]
    },
    {
     "ename": "TypeError",
     "evalue": "'tuple' object does not support item assignment",
     "output_type": "error",
     "traceback": [
      "\u001b[31m---------------------------------------------------------------------------\u001b[39m",
      "\u001b[31mTypeError\u001b[39m                                 Traceback (most recent call last)",
      "\u001b[36mCell\u001b[39m\u001b[36m \u001b[39m\u001b[32mIn[152]\u001b[39m\u001b[32m, line 4\u001b[39m\n\u001b[32m      1\u001b[39m T = (\u001b[33m\"\u001b[39m\u001b[33mRiya\u001b[39m\u001b[33m\"\u001b[39m, \u001b[33m'\u001b[39m\u001b[33mSharma\u001b[39m\u001b[33m'\u001b[39m, \u001b[32m10.5\u001b[39m, \u001b[32m5\u001b[39m)\n\u001b[32m      2\u001b[39m \u001b[38;5;28mprint\u001b[39m (\u001b[33m\"\u001b[39m\u001b[33mT -->\u001b[39m\u001b[33m\"\u001b[39m, T)\n\u001b[32m----> \u001b[39m\u001b[32m4\u001b[39m \u001b[43mT\u001b[49m\u001b[43m[\u001b[49m\u001b[32;43m2\u001b[39;49m\u001b[43m]\u001b[49m = \u001b[32m900\u001b[39m               \n\u001b[32m      5\u001b[39m \u001b[38;5;28mprint\u001b[39m (\u001b[33m\"\u001b[39m\u001b[33mT -->\u001b[39m\u001b[33m\"\u001b[39m, T)\n",
      "\u001b[31mTypeError\u001b[39m: 'tuple' object does not support item assignment"
     ]
    }
   ],
   "source": [
    "T = (\"Riya\", 'Sharma', 10.5, 5)\n",
    "print (\"T -->\", T)\n",
    "\n",
    "T[2] = 900               \n",
    "print (\"T -->\", T)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 153,
   "id": "24924917-b893-4fd9-b789-d32d079b6b8a",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "T --> ('Riya', 'Sharma', 10.5, 5)\n",
      "After Add --> ('Riya', 'Sharma', 10.5, 5, 9.8)\n"
     ]
    }
   ],
   "source": [
    "T = (\"Riya\", 'Sharma', 10.5, 5)\n",
    "print (\"T -->\", T)\n",
    "\n",
    "T1 = list(T)\n",
    "T1.append(9.8)\n",
    "T = tuple(T1)\n",
    "\n",
    "print (\"After Add -->\", T)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 154,
   "id": "375a8316-04bd-42a1-97d9-5cae1f1a67c4",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "T --> ('Riya', 'Sharma', 10.5, 5)\n",
      "After Insert --> ('Riya', 'Sharma', 'Rahul', 10.5, 5)\n"
     ]
    }
   ],
   "source": [
    "T = (\"Riya\", 'Sharma', 10.5, 5)\n",
    "print (\"T -->\", T)\n",
    "\n",
    "T1 = list(T)\n",
    "T1.insert(2, \"Rahul\")\n",
    "T = tuple(T1)\n",
    "\n",
    "print (\"After Insert -->\", T)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 155,
   "id": "a5393c62-e582-4cd1-908a-624cde1af976",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "T --> ('Riya', 'Sharma', 10.5, 5)\n"
     ]
    },
    {
     "ename": "TypeError",
     "evalue": "'tuple' object doesn't support item deletion",
     "output_type": "error",
     "traceback": [
      "\u001b[31m---------------------------------------------------------------------------\u001b[39m",
      "\u001b[31mTypeError\u001b[39m                                 Traceback (most recent call last)",
      "\u001b[36mCell\u001b[39m\u001b[36m \u001b[39m\u001b[32mIn[155]\u001b[39m\u001b[32m, line 3\u001b[39m\n\u001b[32m      1\u001b[39m T = (\u001b[33m\"\u001b[39m\u001b[33mRiya\u001b[39m\u001b[33m\"\u001b[39m, \u001b[33m'\u001b[39m\u001b[33mSharma\u001b[39m\u001b[33m'\u001b[39m, \u001b[32m10.5\u001b[39m, \u001b[32m5\u001b[39m)\n\u001b[32m      2\u001b[39m \u001b[38;5;28mprint\u001b[39m (\u001b[33m\"\u001b[39m\u001b[33mT -->\u001b[39m\u001b[33m\"\u001b[39m, T)\n\u001b[32m----> \u001b[39m\u001b[32m3\u001b[39m \u001b[38;5;28;01mdel\u001b[39;00m \u001b[43mT\u001b[49m\u001b[43m[\u001b[49m\u001b[32;43m1\u001b[39;49m\u001b[43m]\u001b[49m\n\u001b[32m      4\u001b[39m \u001b[38;5;28mprint\u001b[39m (\u001b[33m\"\u001b[39m\u001b[33mAfter Delete -->\u001b[39m\u001b[33m\"\u001b[39m, T)\n",
      "\u001b[31mTypeError\u001b[39m: 'tuple' object doesn't support item deletion"
     ]
    }
   ],
   "source": [
    "T = (\"Riya\", 'Sharma', 10.5, 5)\n",
    "print (\"T -->\", T)\n",
    "del T[1]\n",
    "print (\"After Delete -->\", T)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 156,
   "id": "4994e327-4de8-45df-ad33-d9da07c51424",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "T --> ('Riya', 'Sharma', 10.5, 5)\n",
      "After Delete --> ('Riya', 10.5, 5)\n"
     ]
    }
   ],
   "source": [
    "T = (\"Riya\", 'Sharma', 10.5, 5)\n",
    "print (\"T -->\", T)\n",
    "T1 = list(T)\n",
    "del T1[1]\n",
    "T = tuple(T1)\n",
    "\n",
    "print (\"After Delete -->\", T)"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "49b3a0ef-4f4b-4442-a55d-6b47372a0c25",
   "metadata": {},
   "source": [
    "## Set"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 157,
   "id": "96f5d49e-abf0-4880-98b6-ab39337954de",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Original set           -->  {'F', 'A', 'E', 'D', 'B', 'C'}\n",
      "Num of elements in set -->  6\n"
     ]
    }
   ],
   "source": [
    "s = set(['A', 'B','C','D','C','E', 'F' ])\n",
    "print (\"Original set           --> \", s)\n",
    "print (\"Num of elements in set --> \", len(s))"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 158,
   "id": "7ffd92c5-6f7f-4cd9-8649-921a8dd56b16",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Original set a      -->  {'B', 'F', 'E', 'A'}\n",
      "Original set b      -->  {'E', 'D', 'C', 'A'}\n",
      "Union of a and b    -->  {'F', 'A', 'E', 'D', 'B', 'C'}\n",
      "Intersection of a,b -->  {'E', 'A'}\n",
      "Difference a - b    -->  {'F', 'B'}\n",
      "Difference a - b    -->  {'F', 'B'}\n",
      "Difference b - a    -->  {'C', 'D'}\n",
      "Difference b - a    -->  {'C', 'D'}\n",
      "Symetric Diff a - b -->  {'F', 'D', 'B', 'C'}\n",
      "Symetric Diff b - a -->  {'F', 'D', 'B', 'C'}\n"
     ]
    }
   ],
   "source": [
    "a = set(['A', 'B', 'E', 'F' ])\n",
    "b = set([\"A\", \"C\", \"D\", \"E\"])\n",
    "print (\"Original set a      --> \", a)\n",
    "print (\"Original set b      --> \", b)\n",
    "print (\"Union of a and b    --> \", a.union(b))\n",
    "print (\"Intersection of a,b --> \", a.intersection(b))\n",
    "print (\"Difference a - b    --> \", a - b)\n",
    "print (\"Difference a - b    --> \", a.difference(b))\n",
    "print (\"Difference b - a    --> \", b - a)\n",
    "print (\"Difference b - a    --> \", b.difference(a))\n",
    "print (\"Symetric Diff a - b --> \", a.symmetric_difference(b))\n",
    "print (\"Symetric Diff b - a --> \", b.symmetric_difference(a))"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 160,
   "id": "19ee252b-cae9-4ee5-93c8-f90a67cb16e3",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Original set a       -->  {'B', 'F', 'E', 'A'}\n",
      "Set After Adding (D) -->  {'F', 'A', 'E', 'D', 'B'}\n",
      "Set After Adding (D) -->  {'F', 'A', 'E', 'D', 'B'}\n",
      "Set After Deleting(D)-->  {'F', 'A', 'E', 'B'}\n",
      "Set After pop        -->  {'A', 'E', 'B'}\n",
      "Set After pop        -->  {'E', 'B'}\n"
     ]
    }
   ],
   "source": [
    "a = set(['A', 'B', 'E', 'F' ])\n",
    "print (\"Original set a       --> \", a)\n",
    "a.add(\"D\")\n",
    "print (\"Set After Adding (D) --> \", a)\n",
    "a.add(\"D\")\n",
    "print (\"Set After Adding (D) --> \", a)\n",
    "a.remove(\"D\")\n",
    "print (\"Set After Deleting(D)--> \", a)\n",
    "a.pop()\n",
    "print (\"Set After pop        --> \", a)\n",
    "a.pop()\n",
    "print (\"Set After pop        --> \", a)"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "56a85a77-aef8-4751-b5de-199f18033d25",
   "metadata": {},
   "source": [
    "## Command Line Argument"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 161,
   "id": "7012137c-0fbd-4fe0-9d6a-a78823afbf64",
   "metadata": {},
   "outputs": [],
   "source": [
    "import sys"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 164,
   "id": "200e3c39-e018-4c07-8cba-411f7dd85d10",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "['C:\\\\Users\\\\libra\\\\anaconda3\\\\Lib\\\\site-packages\\\\ipykernel_launcher.py', '-f', 'C:\\\\Users\\\\libra\\\\AppData\\\\Roaming\\\\jupyter\\\\runtime\\\\kernel-d66a542a-9b73-4c7b-bdd7-59bc67f2305f.json']\n"
     ]
    },
    {
     "ename": "ValueError",
     "evalue": "invalid literal for int() with base 10: '-f'",
     "output_type": "error",
     "traceback": [
      "\u001b[31m---------------------------------------------------------------------------\u001b[39m",
      "\u001b[31mValueError\u001b[39m                                Traceback (most recent call last)",
      "\u001b[36mCell\u001b[39m\u001b[36m \u001b[39m\u001b[32mIn[164]\u001b[39m\u001b[32m, line 2\u001b[39m\n\u001b[32m      1\u001b[39m \u001b[38;5;28mprint\u001b[39m(sys.argv)\n\u001b[32m----> \u001b[39m\u001b[32m2\u001b[39m a = \u001b[38;5;28;43mint\u001b[39;49m\u001b[43m(\u001b[49m\u001b[43msys\u001b[49m\u001b[43m.\u001b[49m\u001b[43margv\u001b[49m\u001b[43m[\u001b[49m\u001b[32;43m1\u001b[39;49m\u001b[43m]\u001b[49m\u001b[43m)\u001b[49m \t\u001b[38;5;66;03m# First Number\u001b[39;00m\n\u001b[32m      3\u001b[39m b = \u001b[38;5;28mint\u001b[39m(sys.argv[\u001b[32m2\u001b[39m])\t\u001b[38;5;66;03m# Second Number\u001b[39;00m\n\u001b[32m      4\u001b[39m c = a + b\n",
      "\u001b[31mValueError\u001b[39m: invalid literal for int() with base 10: '-f'"
     ]
    }
   ],
   "source": [
    "print(sys.argv)\n",
    "a = int(sys.argv[1]) \t\n",
    "b = int(sys.argv[2])\n",
    "c = a + b\n",
    "print (a, \" + \", b, \" --> \", c)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 165,
   "id": "9c92ff58-ca22-4661-be3a-a24ef8efeef8",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "-f  +  C:\\Users\\libra\\AppData\\Roaming\\jupyter\\runtime\\kernel-d66a542a-9b73-4c7b-bdd7-59bc67f2305f.json  -->  -f C:\\Users\\libra\\AppData\\Roaming\\jupyter\\runtime\\kernel-d66a542a-9b73-4c7b-bdd7-59bc67f2305f.json\n"
     ]
    }
   ],
   "source": [
    "s = sys.argv[1] + \" \" + sys.argv[2]\n",
    "print (sys.argv[1], \" + \", sys.argv[2], \" --> \", s)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 166,
   "id": "72e7d111-5872-4f48-92b4-9272a4c1a720",
   "metadata": {},
   "outputs": [
    {
     "ename": "ValueError",
     "evalue": "invalid literal for int() with base 10: '-f'",
     "output_type": "error",
     "traceback": [
      "\u001b[31m---------------------------------------------------------------------------\u001b[39m",
      "\u001b[31mValueError\u001b[39m                                Traceback (most recent call last)",
      "\u001b[36mCell\u001b[39m\u001b[36m \u001b[39m\u001b[32mIn[166]\u001b[39m\u001b[32m, line 3\u001b[39m\n\u001b[32m      1\u001b[39m \u001b[38;5;28msum\u001b[39m=\u001b[32m0\u001b[39m\n\u001b[32m      2\u001b[39m \u001b[38;5;28;01mfor\u001b[39;00m s \u001b[38;5;129;01min\u001b[39;00m sys.argv[\u001b[32m1\u001b[39m:]:\n\u001b[32m----> \u001b[39m\u001b[32m3\u001b[39m \t\u001b[38;5;28msum\u001b[39m += \u001b[38;5;28;43mint\u001b[39;49m\u001b[43m(\u001b[49m\u001b[43ms\u001b[49m\u001b[43m)\u001b[49m\n\u001b[32m      5\u001b[39m \u001b[38;5;28mprint\u001b[39m (\u001b[33m\"\u001b[39m\u001b[33mSum is --> \u001b[39m\u001b[33m\"\u001b[39m, \u001b[38;5;28msum\u001b[39m)\n",
      "\u001b[31mValueError\u001b[39m: invalid literal for int() with base 10: '-f'"
     ]
    }
   ],
   "source": [
    "sum=0\n",
    "for s in sys.argv[1:]:\n",
    "\tsum += int(s)\n",
    "\n",
    "print (\"Sum is --> \", sum)"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "9a102fb7-2e12-4eac-87c3-a8509e5fe964",
   "metadata": {},
   "source": [
    "## File Handling"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 167,
   "id": "74ddb13c-64e1-41c4-8923-111acd81f7d3",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Writing done !! \n",
      "Open result.txt to view the content\n"
     ]
    }
   ],
   "source": [
    "fp=open('result.txt','w')\t\n",
    "for  i in range(1,11):\n",
    "\tfp.write(str(i) + \"\\n\")\t\n",
    "fp.close()\n",
    "\n",
    "print (\"Writing done !! \\nOpen result.txt to view the content\")"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 168,
   "id": "39f699f2-d303-41a2-86b8-5056fa1b1a69",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "1\n",
      "2\n",
      "3\n",
      "4\n",
      "5\n",
      "6\n",
      "7\n",
      "8\n",
      "9\n",
      "10\n"
     ]
    }
   ],
   "source": [
    "fp=open('result.txt')\t\t\n",
    "for line in fp: \t\t   \n",
    "\tprint (line.strip())\n",
    "fp.close()"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 169,
   "id": "bfb8eaf7-2f4a-4881-9e72-26a18e4b9793",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Writing done !! \n",
      "Open result.txt to view the content\n"
     ]
    }
   ],
   "source": [
    "Readfp=open('result.txt')\t\t\n",
    "Writefp=open('abc.txt','w')\t\n",
    "for line in Readfp:\n",
    "\tWritefp.write(line.upper())\n",
    "\n",
    "Writefp.close()\n",
    "Readfp.close()\n",
    "\n",
    "print (\"Writing done !! \\nOpen result.txt to view the content\")"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "48e32cf0-3a85-42d3-8a3f-55eb1d94d902",
   "metadata": {},
   "outputs": [],
   "source": []
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3 (ipykernel)",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.13.9"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 5
}
