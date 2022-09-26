# WhitePassword

https://www.linkedin.com/posts/santanu-banerjee-093929150_github-santanbanwhitepassword-random-activity-6928894840805957632-I4rN?utm_source=linkedin_share&utm_medium=member_desktop_web

Random Password generator using Python which generates a password and prints it into an MS-Word and PDF file with Font Colour as White. This is the safest way to generate a password for any activity on teh internet and either allow the browser to remember it, to store this in a some storage device. The password may be used by copying the contents so that anyone viewing your screen will also not be able to see your password (including you).

# Remember to clear your clipboard which stores the password temporarily while copying and using it.

The user enters the permissible length of the password as input.

Random values among these options are then chosen.

all_keyboard_entity={1: '`', 2: '1', 3: '2', 4: '3', 5: '4', 6: '5', 7: '6', 8: '7', 9: '8', 10: 'N', 11: '9', 12: '0', 13: '-', 14: '=', 15: 'q', 16: 'w', 17: 'e', 18: 'r', 19: 't', 20: 'y', 21: 'u', 22: 'i', 23: 'o', 24: 'p', 25: '[', 26: ']', 27: '\\', 28: 'a', 29: 's', 30: 'd', 31: 'f', 32: 'g', 33: 'h', 34: 'j', 35: 'k', 36: 'l', 37: ';', 38: "'", 39: 'z', 40: 'x', 41: 'c', 42: 'v', 43: 'b', 44: 'n', 45: 'm', 46: ',', 47: '.', 48: '/', 49: '~', 50: '!', 51: '@', 52: '#', 53: '$', 54: '%', 55: '^', 56: '&', 57: '*', 58: '', 59: '(', 60: ')', 61: '_', 62: '+', 63: '{', 64: '}', 65: '|', 66: ':', 67: '"', 68: '<', 69: '>', 70: '?', 71: 'Q', 72: 'W', 73: 'E', 74: 'R', 75: 'T', 76: 'Y', 77: 'U', 78: 'I', 79: 'O', 80: 'P', 81: 'A', 82: 'S', 83: 'D', 84: 'F', 85: 'G', 86: 'H', 87: 'J', 88: 'K', 89: 'L', 90: 'Z', 91: 'X', 92: 'C', 93: 'V', 94: 'B', 95: 'M', 96: ' '}

It may be noted that the Python random funtion available isn't very good with respect to its distribution of choices; and therefore it is necessary to have a better random generator which would be pure random number generator (like IBM Quantum Computers could be integrated using Qiskit)

An Image Folder is also provided which highlightes the frequency of the choices among 96 entities. As we progressively increase the number of choices, the Standard Deviation increases which definitely tell that the probability of choosing all numbers are not equal. [This may be therefore compared similarly to a random number generated using a Quantum Computer].
