class Book {
    constructor(title, author) {
        this.title = title;
        this.author = author;
        this.available = true;
    }
 }
 class LibraryMember {
    constructor(name, email) {
        this.name = name;
        this.email = email;
        this.borrowedBooks = [];
    }
    borrowBook(book) {
        if (book.available) {
            book.available = false;
            this.borrowedBooks.push(book);
            return `${this.name} has successfully borrowed '${book.title}' by ${book.author}.`;
        } else {
            return `Sorry, '${book.title}' is currently unavailable.`;
        }
    }
    returnBook(book) {
        if (this.borrowedBooks.includes(book)) {
            book.available = true;
            this.borrowedBooks = this.borrowedBooks.filter(b => b !== book);
            return `${this.name} has successfully returned '${book.title}' by ${book.author}.`;
        } else {
            return `You didn't borrow '${book.title}' from the library.`;
        }
    }
    displayBorrowedBooks() {
        if (this.borrowedBooks.length === 0) {
            return `${this.name} has not borrowed any books.`;
        } else {
            const bookList = this.borrowedBooks.map(book => book.title).join(', ');
            return `${this.name} has borrowed the following books: ${bookList}.`;
        }
    }
 }
 class LibraryStaff {
    static addBook(library, title, author) {
        const newBook = new Book(title, author);
        library.push(newBook);
        return `Added '${title}' by ${author} to the library.`;
    }
    static removeDamagedBook(library, book) {
        const index = library.indexOf(book);
        if (index !== -1) {
            library.splice(index, 1);
            return `Removed '${book.title}' by ${book.author} from the library due to damage.`;
        } else {
            return 'The specified book is not in the library.';
        }
    }
 }

 const librarian = new LibraryStaff();
 
 const library = [
    new Book("The Catcher in the Rye", "J.D. Salinger"),
    new Book("To Kill a Mockingbird", "Harper Lee"),
    new Book("1984", "George Orwell")
 ];

 const member = new LibraryMember("John Doe", "john.doe@email.com");

 console.log(LibraryStaff.addBook(library, "The Great Gatsby", "F. Scott Fitzgerald"));
 
 console.log(member.borrowBook(library[0]));
 
 console.log(member.returnBook(library[0]));

 console.log(member.displayBorrowedBooks());
 
 console.log(LibraryStaff.removeDamagedBook(library, library[1]));
