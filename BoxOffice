#include <iostream>
#include <iomanip>
int main() {
/*
Lab 1: Box Office
Giovanny Rodriguez Rivera
801-24-2694
Prof. Lillian Gonzalez
*/

    // Precio de tickets y el porcentage que recibe el cine
    const double ADULT_PRICE = 10.00;
    const double CHILD_PRICE = 6.00;
    const double THEATER_PERCENT = 0.20;

    // Declarar variables
    std::string movie;
    int adultTickets, childTickets;

    // Desplegar el proposito del programa
    std::cout << "This program calculates the Gross and Net Box Office Profit and the Distributor's Profit of a movie playing in the theater.\n\n";

    // Obtener los inputs del usuario
    std::cout << "Enter the name of the movie: ";
    std::getline(std::cin, movie);
    std::cout << "Enter the amount of adult tickets sold: ";
    std::cin >> adultTickets;
    std::cout << "Enter the amount of child tickets sold: ";
    std::cin >> childTickets;
    std::cout << "\n";

    // Calcular las ganancias
    double grossProfit = adultTickets * ADULT_PRICE + childTickets * CHILD_PRICE;
    double netProfit = grossProfit * THEATER_PERCENT;
    double distributorPayment = grossProfit - netProfit;

    // Establecer el formatting
    std::cout << std::fixed << std::showpoint << std::setprecision(2);

    // Desplegar los resultados
    std::cout << std::left << std::setw(30) << "Movie Name:" 
    << std::right << "\"" << movie << "\"" << "\n";
    std::cout << std::left << std::setw(30) << "Adult Tickets Sold:" 
    << std::right << std::setw(10) << adultTickets << "\n";
    std::cout << std::left << std::setw(30) << "Child Tickets Sold:" 
    << std::right << std::setw(10) << childTickets << "\n";
    std::cout << std::left << std::setw(30) << "Gross Box Office Profit:" 
    << std::right << "$" << std::setw(11) << grossProfit << "\n";
    std::cout << std::left << std::setw(30) << "Net Box Office Profit:" 
    << std::right << "$" << std::setw(11) << netProfit << "\n";
    std::cout << std::left << std::setw(30) << "Amount Paid to Distributor:" 
    << std::right << "$" << std::setw(11) << distributorPayment << "\n";

    return 0;
}