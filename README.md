# LISTAARRAY

package arrayl;

import java.util.ArrayList;

public class ArrayL {

    public static void main(String[] args) {
        // CRIANDO OBJ LINTA
        ArrayList<String> lista = new ArrayList<>();

        // ADICIONAR ITENS A LISTA
        lista.add("a");
        lista.add("b");
        lista.add("d");
        lista.add("e");

        // mostrar elementos 
        System.out.println(lista);
        System.out.println("...........................................................");

        // adicionar elemento em determinada posiçao
        lista.add(2, "c");
        System.out.println(lista);
        System.out.println("...........................................................");

        // buscar elemento em posição delerminada
        System.out.println(lista.get(0));
        System.out.println("...........................................................");

        // percorrer a lista
        for (int n = 0; n < lista.size(); n++) {
            System.out.println(lista.get(n) + "=" + n);

        }

        // percorre com for Each
        for (String item : lista) {
            System.out.println(item);

        }

        // pesquisar elementos 
        System.out.println("...........................................................");
        System.out.println(lista.contains("a"));
        System.out.println(lista.contains("f"));
        System.out.println("...........................................................");
        
        // remover elementos 
        lista.remove("d");
        System.out.println(lista);
        
        

    }

}

