# README

rails g scaffold Component name:string code:string description:text minimum:float maximum:float uom:string is_binary:boolean

rails g scaffold Analysis user:references component:references value:string date:datetime