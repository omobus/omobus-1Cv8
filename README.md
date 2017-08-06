# OMOBUS -> 1Cv8

Общее описание и требования к конфигурации
Модуль предназначен для использования в составе конфигураций «1С Управление Торговлей 10.3». 
Версия конфигурации должна быть не менее 10.3.17. На более ранних версиях тестирование не 
производилось и работоспособность модуля не гарантируется. Модуль должен работать в среде 
операционной системы Windows. Последнее ограничение обусловлено тем, что штатная работа 
платформы не позволяет обрабатывать архивы нужных типов. Если возникнет необходимость 
использования платформы 1С в других операционных системах, придется отказаться от сжатия файлов.
Для использования модуля необходимо внести изменения в типовую конфигурацию. Перед началом 
добавления убедитесь, что в настройках обновления включена возможность изменения типовой 
конфигурации, если конфигурация находится на поддержке (так же допустим вариант снятия 
конфигурации с поддержки).

Для подключения модуля необходимо выполнить сравнение и объединение конфигурации с файлом 
patch.pdf, входящим в комплект поставки. Детальная инструкция по процедуре объединения
конфигураций приводится в файле patch.pdf.


# LICENSE

Copyright (c) 2006 - 2017 ak-obs, Ltd. <info@omobus.net>
All rights reserved.

This program is a free software. Redistribution and use in source
and binary forms, with or without modification, are permitted provided
that the following conditions are met:

1. Redistributions of source code must retain the above copyright
   notice, this list of conditions and the following disclaimer.

2. The origin of this software must not be misrepresented; you must
   not claim that you wrote the original software.

3. Altered source versions must be plainly marked as such, and must
   not be misrepresented as being the original software.

4. The name of the author may not be used to endorse or promote
   products derived from this software without specific prior written
   permission.

THIS SOFTWARE IS PROVIDED BY THE AUTHOR ``AS IS'' AND ANY EXPRESS
OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED
WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE
ARE DISCLAIMED.  IN NO EVENT SHALL THE AUTHOR BE LIABLE FOR ANY
DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL
DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE
GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS
INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY,
WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING
NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS
SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
