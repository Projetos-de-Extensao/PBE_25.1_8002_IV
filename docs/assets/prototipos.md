@startuml
' Usa o modo salt para wireframes
salt
{
{+
{Tela de Login}
[ E-mail       |______         ]
[ Senha        |______         ]
[ Entrar                         ]

}

{+
{Painel do Administrador}
[ Criar novo perfil       ]
[ Acessar formulários     ]
[ Alterar dados           ]
}

}
@enduml


@startuml
salt
{
{+
{Tela de Cadastro de Administrador}

[ Nome Completo       |________ ]
[ E-mail              |________ ]
[ Senha               |________ ]
[ Confirmar Senha     |________ ]
[ Tipo de Perfil      | ( ) ReCenseador   ( ) Adm_Site ]

[ Criar Conta ]
[ Voltar para Login ]

}
}
@enduml





@startuml
salt
{
{+
{Painel do Administrador}

[ Bem-vindo, Administrador! ]

[ 🧾 Criar Novo Perfil      ]
[ 📄 Acessar Formulários    ]
[ 📝 Alterar Dados do Perfil ]

----

[ 🔒 Sair ]

}
}
@enduml






@startuml
salt
{
{+
{Criar Novo Perfil}

[ Nome Completo       |________ ]
[ E-mail              |________ ]
[ Senha               |________ ]
[ Confirmar Senha     |________ ]

[ Tipo de Perfil      | ( ) ReCenseador   ( ) Adm_Site ]

----

[ ✅ Salvar Perfil ]
[ 🔙 Voltar ao Painel ]

}
}
@enduml





@startuml
salt
{
{+
{Alterar Dados do Perfil}

[ Selecionar Perfil     | [▼ Lista de Perfis] ]

----

[ Nome Completo         |________ ]
[ E-mail                |________ ]
[ Senha (opcional)      |________ ]
[ Confirmar Nova Senha  |________ ]

[ Tipo de Perfil        | ( ) ReCenseador   ( ) Adm_Site ]

----

[ 💾 Salvar Alterações ]
[ 🔙 Voltar ao Painel ]

}
}
@enduml




@startuml
salt
{
{+
{Formulários Disponíveis}

[ 🔘 Formulário: Domicílio ]
[ 🔘 Formulário: Dados Pessoais ]
[ 🔘 Formulário: Identificação Étnico-Racial ]
[ 🔘 Formulário: Nível de Instrução ]
[ 🔘 Formulário: Situação Familiar ]
[ 🔘 Formulário: Condições de Moradia ]

----

[ 🔍 Abrir Formulário Selecionado ]
[ 🔙 Voltar ao Painel ]

}
}
@enduml


