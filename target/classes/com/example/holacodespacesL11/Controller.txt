package com.example.holacodespacesL11;

import java.lang.String;
import org.springframework.web.bind.annotation.RestController;
import org.springframework.web.bind.annotation.RequestMapping;
import org.springframework.web.bind.annotation.GetMapping;

@RestController
@RequestMapping(path="/")
public class Controller{

    @GetMapping(path="/")
    public String CodNom(){
        return "Sm75695765-Jefferson Onsihuay";
    }

    @GetMapping(path="/idat/codigo")
    public String Cod(){
        return "Sm75695765";
    }

    @GetMapping(path="/idat/nombre-completo")
    public String Nom(){
        return "Jefferson Jesús Onsihuay Malpartida";
    }
}